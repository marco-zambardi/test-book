# Creating a custom demographic rule

**Note:**  
See [Data types, input fields and operators](InputBoxOperators.md) for more about the fields and operators that are available in the UI.  

When you click **Create custom rule**, the **new demographic custom rule** page displays, with the name of the segment shown as its title and **Demographic** highlighted in a small box. The system automatically generates a **Rule name**, consisting of the words **New rule** and the time. Do the following:  

1. Select the system generated name and enter one of your choice.  
  Ensure that the name you use is unique, descriptive of the rule, and can easily be recognized by yourself and others in the future.  
2. Under **Match**, select whether the contacts that are to be identified by the rule should match **ALL** of the conditions you define in the next steps, or **ANY** of them.  
  **Note:**  
  If you select **ALL**, the number of relevant contacts in the database, which is displayed to the right of the page at the top and bottom, reduces as each condition is applied. If you select **ANY**, the number of contacts increases. See [Understanding segmentation](UnderstandingSegmentation.md) for more details.  
3. Define the conditions that apply to the rule, as follows:  
  - The system displays pre-configured demographic conditions, for example:  
    - **Name**  
    - **Surname**  
    - **Gender**  
  - You can choose to:  
    - Apply none, one or any combination of these conditions  
    - or:  
    - Delete them as appropriate, by clicking the **Bin** icon.  
  
   **Note:**  
   The conditions that are initially displayed are configured on a customer-by-customer basis, when the system is set up. They can be changed at any time, using the **Segmentation settings** page, which can be accessed through the **Settings** tab in the **Control bar**. See [Segmentation Settings] for more details.  

   To apply, for example, the **Name** condition:  
    - Click the downwards pointing arrow to the right of the first box, and select the appropriate operator, for example, **Not equal to**, from the drop-down list  
    - Enter the required first name, for example, John, in the **Free text search** field  
   (The **Gender** condition has a drop-down list instead of a search field..md)  
   The system displays the number of contacts in the database that match the condition.  
  ***Tip:***  
  If, for example, you want to search for two first names, such as James and John, you can either create two rules, or set **Match** to **ANY** and add another **Name** condition for the second name. See below for details about adding further conditions.  
  - Continue to define the standard conditions as required  
4. Add further conditions, as follows:  
  - In the **Add condition** panel, click the downwards pointing arrow to the right of the box, and select the appropriate condition, for example, **Country**, from the drop-down list  
   The new condition is added to the list.  
  - Click the downwards pointing arrow to the right of the first box, and select the appropriate operator, for example, **Equal to**, from the drop-down list  
    **Note:**  
   The first box may display a different list of operators, according to the type of condition being defined.  
  - Enter the appropriate value in the second box  
    **Note:**  
   Depending upon the condition that you are defining, the second box may be:  
      - An automated search field  
      - A free text search field  
      - A drop-down list  
      - A date and time field  
      - A numeric data field  
      - A checkbox  

5. When you are finished, click **Add** to apply the rule to the segment, or **Cancel** to abort the process.  
  You are returned to the **New segment** page and the rule is added to the **Rule list** area of the **Summary panel**.  

***Next page:***  
[Creating a digital messages rule](CreatingDigitalMessagesRule.md)  

----------

## Related Pages:  

- [Managing segments](ManagingSegments.md)  
  - [Viewing segments](ViewingSegments.md)  
  - [Segment details](SegmentDetails.md)  
- [Creating new segments](CreatingNewSegments.md)  
  - [Creating a demographic rule](CreatingDemographicRule.md)  
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
