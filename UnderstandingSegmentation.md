# Understanding segmentation

Contactplan enables you to create segments from the appropriate database, using the following data categories:  

- Demographic data  
- Behavioral data regarding previous digital messages  
- behavioral data regarding online and offline purchases  

The contactplan architecture has been purpose-designed to be capable of handling any other kind of event, simply by applying the appropriate system configuration.  

## Segments, rules and conditions  

Segments are identified by applying one or more defined rules. Each rule is composed of a set of conditions. Conditions are selection criteria that are combined to make up a rule, which is then applied to a specific category of data, for example a demographic rule, or a purchases rule.  

A segment can include two or more rules that are applied to the same category of data, such as two digital message rules.  

### Combining conditions within a rule  

Conditions within a rule are combined by applying either the ALL or the ANY option, when using the UI to create the rule.  

#### ALL  

If the ALL option is applied, only those contacts that match all of the conditions that make up the rule are selected. The result is similar to applying an AND logical operator.  

#### ANY  

If the ANY option is applied, any contacts that match at least one of the conditions that make up the rule are selected. The result is similar to applying an OR logical operator.  

### Combining segment rules

Two rules that make up a segment, such as rule A and rule B, can be combined using AND, OR or EXCEPT logic operators, also referred to as **interaction conditions**.

#### AND  

The result is the set of contacts that match both the first and the second rule. This is equivalent to the intersection of contacts selected by both rules.  

#### OR  

The result is the set of contacts that match either the first or the second rule. This is equivalent to the union of contacts selected by each rule.  

#### EXCEPT  

The result is the set of contacts that are selected by the first rule, but not by the the second rule. This is equivalent of subtracting the contacts selected by rule B from those selected by rule A.  

When more than two rules are used to define a segment, the system applies the interaction conditions sequentially. Contactplan starts by calculating the result of combining the first and second rule. This result is then combined with the third rule, using the interaction conditions between the second and third rule, and so on.  

### Time frame conditions  

Behavioral data can also be referred to as events or actions, because each item of data occurs at a precise moment in time. When creating or editing an event rule, meaning a rule that is applied to behavioral data, you can choose whether the applicable conditions are applied to:  

- All the events, regardless of when they occurred  
- or:  
- Only those events that happened in a given time frame  

This is know as a time frame condition.  

A time frame condition can be:

- Anytime  
  All events are taken into account.  
- In date range
  Only events that occurred after a given date, before a given date, or between two dates are taken into account.  
- In the last
  Only events that occurred in the last **N** days, weeks, or months are taken into account.  

Time frame conditions cannot be applied to demographic rules, as the data is not made up of events.  

## Special queries  

Contactplan provides a simple way to create a segment with complex conditions, without needing to write any code or a script. Contactplan supports the following kinds of special queries:  

- Analytical queries  
- Correlation-based queries  

### Analytical queries  

**Example:**  

- All those contacts that bought a yellow bag _**on at least 10% of the occasions**_ they purchased something  
  or:  
- All those contacts that spent more than 200 euro _**on less than 5% of the occasions**_ they spent money  
An analytical query enables a comparison to be made between how often an event with specific conditions occurs, for example, buying a yellow bag, or spending more the 200 euro, and all events of the same kind, such as making a purchase.  

### Correlation-based queries  

**Example:**  

- All those contacts that bought a yellow bag _**within 5 days from**_ having opened the *'New yellow bags in store!'* newsletter  
  or:  
- All those contacts that placed an order _**more than 30 days after**_ having clicked on the link in the newsletter  

A correlation-based query enables a relationship between two different events during a given period of time to be established.  

***Next page:***  
[Understanding plans](UnderstandingPlans)  

----------

## Related Pages:  

- [Understanding contactplan](UnderstandingContactPlan)  
  - [Using the UI](UsingUI)  
  - [Understanding plans](UnderstandingPlans)  
  - [Reports and dashboard analysis](ReportsAndDashboardAnalysis)  

### Also see:  

- [Managing segments](ManagingSegments)  
- [Managing plans](ManagingPlans)  
- [Managing settings](ManagingSettings)
- [Managing reports]  

### Other links:  

- [ContactLab contactplan](Home)  
- [Data types, input fields and operators](InputBoxOperators)  
- [Glossary]  
