# Bootstrap project

Clone the locales repo into locales folder
```bash
  git clone git@github.com:contactlab/explore.contactlab.com.contents.git locales
```

Run
```bash
  bundle
```
to install middleman and its dependencies.

Run
```bash
  npm install
```
to install all the node.js modules

Run
```bash
  brew update
  brew install elasticsearch
```
to install elasticsearch in your Mac OSX enviroment.

Get elasticsearch configuration file information from homebrew:
```bash
brew info elasticsearch
```

Configure elasticsearch:
```bash
nano /usr/local/etc/elasticsearch/elasticsearch.yml
```

Add the following lines to elasticsearch.yml:
```
http.cors.allow-origin: "/.*/"
http.cors.enabled: true
discovery.zen.ping.multicast.enabled: false
```

You can run elasticsearch using LaunchRocket (if you installed it) or by command line, for example `brew services start elasticsearch` or `launchctl load ~/Library/LaunchAgents/homebrew.mxcl.elasticsearch.plist` or `elasticsearch --config=/usr/local/opt/elasticsearch/config/elasticsearch.yml`

# Aggiornamento pacchetti

per aggiornare i pacchetti con NPM ed aggiornare il `package.json` con le versioni:

```bash
  npm outdated --depth=0 | grep -v Package | awk '{print $1}' | xargs -I% npm install %@latest --save
```

# Connessione al server di staging

Si passa attraverso `code.welaika.com`. Aggiungere queste righe ad `~/.ssh/config`:

```bash
  Host code
    HostName 92.243.31.218
    Compression yes
    Port 22
    User root

  Host contactlab
    HostName staging.contactlab.com
    Compression yes
    Port 22024
    User welaika
    ProxyCommand ssh code -W %h:%p
```

FYI: Per impostare automaticamente la password e non inserirla ogni volta basta usare ssh-copy-id
```bash
ssh-copy-id contactlab
```

# Enviroments configuration

To build for the staging enviroment in the staging server you should run

```bash
  middleman build -e staging
```

It loads the `enviroments/staging.rb` configuration file and run the build. Thanks to the `mm-contactlab-deploy` extension, it will copy all the build to the correct folder.

# Crontab configuration

```bash
*/10 * * * * /usr/bin/bash -l -c "cd /home/middleman/contactlab-middleman/ && ./build-site.sh"
```

Each 10 minutes run the command (with rbenv and all the stuff of .bash_profile) "cd /home/middleman/contactlab-middleman/ && ./build-site.sh"

## Node and other commands

Node should be accessible by crontab. In the staging enviroment we added the path of it

```bash
PATH=$PATH:$HOME/.local/bin:$HOME/bin:$HOME/contactlab-middleman/bin:/usr/local/bin
```

(You can get the path `node`, `/usr/local/bin` in this case, using the command `which node` )

