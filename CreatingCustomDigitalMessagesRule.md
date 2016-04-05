# Creating a custom digital messages rule

**Note:**  
See [Data types, input fields and operators](InputBoxOperators.md) for more about the fields and operators that are available in the UI.  

When you click **Create custom rule**, the **new digital messages custom rule** page displays, with the name of the segment shown as its title and **Digital Messages** highlighted in a small box. The system automatically generates a **Rule name**, consisting of the words **New Digital Messages** and the time. Do the following:  

1. Select the system generated name and enter one of your choice.  
  Ensure that the name you use is unique, descriptive of the rule, and can easily be recognized by yourself and others in the future.  
2. Under **Action**, click the downwards pointing arrow to the right of the box, and select the appropriate digital message action for the rule, for example, **Have not clicked**.  
  **Note:**  
  The following digital message actions are available:  
  - Have received  
    Contacts that have been included in the delivery list  
  - Have not received  
    Contacts that have not been included in the delivery list  
  - Have opened  
    Contacts that have opened messages  
  - Have not opened  
    Contacts that have not opened messages  
  - Have clicked  
    Contacts that have clicked on a link in messages  
  - Have not clicked  
    Contacts that have not clicked on a link in messages  
3. Under **Time frame**, select when the digital message action should have taken place. Three options are available:  
  - **Anytime**  
    The action can have taken place at any time. No further options are displayed.  
  - **In the date range**  
    The action must have taken place:  
    - After the first date  
      Only the first date field is completed.  
    - Before the second date  
      Only the second date field is completed.  
    - Between two dates.  
      Both date fields are completed.  

    Click the **Calendar** icon in each box and define the date range.  
  - **In the last...**  
    The action must have taken place in the defined time period.  
     - Enter a numeric value in the first box, for example, **3**  
     - Click the downwards pointing arrow to the right of the second box, and select **days**, **weeks**, **months**, or **years**  
2. Under **Match**, select whether the contacts that are to be identified by the rule, should match **ALL** of the conditions you define in the next steps, or **ANY** of them.  
  **Note:**  
  If you select **ALL**, the number of relevant contacts in the database, which is displayed to the right of the page at the top and bottom, reduces as each condition is applied. If you select **ANY**, the number of contacts increases. See [Understanding segmentation](UnderstandingSegmentation.md) for more details.  
3. Define the conditions that apply to the rule, as follows:  
  - The system displays pre-configured digital messages conditions, for example:  
    - **Delivery ID**  
      The delivery identifier.  
    - **Subject**  
      The subject of the delivery.  
  - You can choose to:  
    - Apply none, one or any combination of these conditions  
    - or:  
    - Delete them as appropriate, by clicking the **Bin** icon.  
  
    To apply, for example, the **Delivery ID** condition:  
    - Click the downwards pointing arrow to the right of the first box, and select the appropriate operator, for example, **Not equal to**, from the drop-down list  
    - Enter a **numerical value**, if appropriate to the defined operator, in the remaining box or boxes  
      For example, If you have selected **Not equal to**, there is one numerical field. If you have selected **Between**, there are two numerical fields. If you have selected **is null**, the numerical field cannot be edited.  
  
    To apply, for example, the **Subject** condition:  
    - Click the downwards pointing arrow to the right of the first box, and select the appropriate operator, for example, **Not equal to**, from the drop-down list  
    - Enter the required subject, for example, Welcome, in the **Search** field  
  
     The system displays the number of contacts in the database that match the condition/s.  
     ***Tip:***  
     If, for example, you want to search for two subjects, such as Welcome and Happy Birthday, you can either create two rules, or set **Match** to **ANY** and add another **Subject** condition. See below for details about adding further conditions.  

  - Continue to define the pre-configured conditions as required.  
  
4. Add further conditions, as follows:  
  - In the **Add condition** panel, click the downwards pointing arrow to the right of the box, and select the appropriate condition, for example, **Country code**, from the drop-down list  
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

## % threshold condition  

The **% threshold** condition is used to identify contacts whose activities satisfy a percentage range that is applied to a specific event type, while also meeting the other conditions defined for the rule. For example, contacts who have opened messages with the subject "special offer" on more than 10% of the occasions that they have opened messages.  

**Note:**  
The **% threshold** condition can only be applied if at least one other condition is set in addition the **Action** and **Time frame** fields.  

***Next page:***  
[Creating a purchases rule](CreatingPurchasesRule.md)  

----------

## Related Pages:  

- [Managing segments](ManagingSegments.md)  
  - [Viewing segments](ViewingSegments.md)  
  - [Segment details](SegmentDetails.md)  
- [Creating new segments](CreatingNewSegments.md)  
  - [Creating a demographic rule](CreatingDemographicRule.md)  
  - [Creating a custom demographic rule](CreatingCustomDemographicRule.md)  
  - [Creating a digital messages rule](CreatingDigitalMessagesRule.md)  
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
