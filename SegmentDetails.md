# Segment details

*Insert Edit Segment screen shot...*  

The details of a particular segment are displayed in the **Edit segment** page, which includes the following fields, controls and panels:  

- The segment name  
- Controls to add further rules to the segment  
  See [Editing a segment](EditingSegment.md) for more details.  
- The **Summary** panel  
  Positioned to the right of the page.  
- A series of buttons at the bottom of the page:  
  - **Back to segments list**  
   Returns you to the **Segments list** view of the **My segments** page.  
  - **Delete**  
   Deletes the segment.  
   See [Deleting a segment](DeletingSegment.md) for more details.  
   **Note:**  
   This action cannot be reversed.  
  - **Save**  
   Saves the segment.  
  - **Download contacts list**  
   Downloads the contact list defined by the segment to your computer, in CSV format. See [Downloading a segment contact list](DownloadingSegmentContactList.md) for more details.  
  - **Start new plan**  
   Enables you to create a new plan, which uses the current segment, by opening the **New plan** page. See [Creating new plans](CreatingNewPlans.md) for more details.  

## Summary panel  

The **Summary** panel displays:  

- Three icons, positioned to the top right of the panel  
  - **Download a contact list** in CSV format  
  - **Open the segment dashboard**  
  - **View the list of segment contacts**  
  See [Getting started and navigating the UI](NavigatingUI.md) for more details about the icons.  
- The existing rule/s that define the segment  
- The interaction condition or operator, which logically combines each rule with the previous one  
- The total number of contacts that the segment includes  

The **Summary** panel is also included in the **New segment** page.  

### Segment rules

Each rule is displayed as a card, with the following details:  

- The rule name  
- The type of rule  
  A Demographic, Digital messages or Purchases rule.  
- A **Pencil** icon  
 Click to edit the rule.  
- A **Bin** icon  
  Click to delete the rule.  
  **Note:**  
  This action cannot be reversed.  
- The number of contacts selected by the rule  

#### Interaction condition controls  

When there are two or more rules, each rule pair is separated by **interaction condition** controls. These determine how two rules interact together to define contacts. The available interaction conditions are:

- **AND**  
  Only the contacts that conform with both rules are included in the total contacts for segment.  
- **OR**  
  The contacts that conform with either rule are included in the total contacts for segment.  
- **EXCEPT**  
  The contacts that are defined by the second rule are removed from those identified by the first rule.  

When there are three or more rules, the interaction conditions are applied in the order that the rules appear in the summary list. For example, the condition between rules one and two is applied before the one between rules two and three. This means that the condition between rules two and three is applied to the result of the one between rules one and two.  

See [Editing a segment](EditingSegment.md) for more about changing the properties of a segment.  

***Next page:***  
[Creating new segments](CreatingNewSegments.md)  

----------

## Related Pages:  

- [Managing segments](ManagingSegments.md)  
  - [Viewing segments](ViewingSegments.md)  
- [Creating new segments](CreatingNewSegments.md)  
  - [Creating a demographic rule](CreatingDemographicRule.md)  
  - [Creating a custom demographic rule](CreatingCustomDemographicRule.md)  
  - [Creating a digital messages rule](CreatingDigitalMessagesRule.md)  
  - [Creating a custom digital messages rule](CreatingCustomDigitalMessagesRule.md)  
  - [Creating a purchases rule](CreatingPurchasesRule.md)  
  - [Creating a custom purchases rule](CreatingCustomPurchasesRule.md)  
- [Editing a segment](EditingSegment.md)  
- [Deleting a segment](DeletingSegment.md)  
- [Downloading a segment contact list](DownloadingSegmentContactList.md)  
- [Creating a new plan directly from a saved segment](CreatingPlanFromSegment.md)  

### Also see:  

- [Managing plans](ManagingPlans.md)  
- [Managing reports]  
- [Managing settings](ManagingSettings.md)  
  - [Segmentation settings]  
  - [Local settings](LocalSettings.md)  
  - [Managing DND policy settings](ManagingDND.md)  
  - [Managing users]  

### Other links:  

- [ContactLab contactplan](Home.md)  
- [Data types, input fields and operators](InputBoxOperators.md)  
- [Glossary]  