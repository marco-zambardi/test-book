# Understanding plans

A plan includes all of the information that is required to make use of the contacts identified in a segment, for example, as the target audience for newsletters and other marketing activities.  

## Plan components  

Plans include the following information, as a minimum:  

- The target date, time and timezone to carry out the plan  
- The target segment to be used (contacts)  
- The consumer  
  The external platform that is to receive the list of contacts  

The following can also be defined in a plan:  

- Whether it is a single-shot or a recurring plan  
- The Do Not Disturb (DND) policy  
  To manage the volume of messages sent to contacts  
- Test email addresses  
  To send a test delivery before the actual one  

### Target audience  

The target audience of a plan is defined by:

- The contacts selected by the segment  
- Any DND policy that is applied  
  All contacts that have already reached the maximum number of communications allowed by the policy are removed.  

## Plan processing  

The resulting list of contacts is passed to the selected consumer for the plan to be executed. The following consumers are provided by contactplan as standard:  

- A ContactLab plugin
  Used for email, SMS and Push deliveries through the ContactLab platform.  
- An SFTP plugin  
  Saves the list of contacts to an external space, from where it can be retrieved manually, or by another system.  

The contactplan architecture has been designed so that a new plugin can be added, without a loss of service.  

***Next page:***  
[Reports and dashboard analysis](ReportsAndDashboardAnalysis)  

----------

## Related Pages:  

- [Understanding contactplan](UnderstandingContactPlan)  
  - [Using the UI](UsingUI)  
  - [Understanding segmentation](UnderstandingSegmentation)  
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
