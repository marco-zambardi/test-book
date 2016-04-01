# Creating new segments

*Insert New segment screen shot...*  

**Note:**  
See [Data types, input fields and operators](InputBoxOperators.md) for more about the fields and operators that are available in the UI.  

To create a new segment, do the following:

1. Click the **Segments** tab.  
  The **My segments** page displays.  
2. Click **Create new segment**.  
  The **New segment** page displays, and the system automatically generates a segment name, consisting of the words **New segment** and the current date.  
3. Select the system generated name and enter one of your choice.  
  Ensure that the name you use is unique, descriptive of the segment, and can easily be recognized by yourself and others in the future.  
4. Depending upon the rule/s that you want to define for the segment, click one of the following:  
  - [Create demographic rule](CreatingDemographicRule.md)  
  - [Create digital messages rule](CreatingDigitalMessagesRule.md)  
  - [Create purchases rule](CreatingPurchasesRule.md)  

  and follow the instructions on the relevant page of this guide to add a rule for that category. See the *Contactplan Product Overview* for a detailed description of rules and query types.  

  When a rule is created:  
  - You are returned to the **New segment** page  
  - The rule is added to the **Rule list** area of the **Summary panel**, which is displayed to the right of the **New segment** page. See [Segment details](SegmentDetails.md) for more about the **Summary panel**.  
5. Repeat **Step 4** and the rule creation instructions as often as required, to continue to add rules in any of the available categories.  
  
  **IMPORTANT:**  
  When you are creating more than one rule, you need to ensure that you define them in the correct order, so that you can apply the appropriate **interaction condition** between a pair of rules. See **Step 6** and [Segment details](SegmentDetails.md) for more about **interaction conditions**. The current release does not allow the order of rules in the **Rule list** to be changed, once they have been defined.  
  
  **Note:**  
  If you are creating, for example, a segment with a number of rules, it is advisable to save the segment when you have added one or two rules, then edit it to add further rules. See [Editing a segment](EditingSegment.md) for more details.  
6. When you have defined two or more rules, you need to determine how one rule in the **Rule list** interacts with the next rule. Do the following:  
  - In the **Summary panel**, positioned to the right of the **New segment** page, locate two consecutive rules in the list and select the appropriate **interaction condition**, from those listed in the area between the two rules. See [Segment details](SegmentDetails.md) for more about **interaction conditions**.  
7. When the segment and the associated rules are defined as intended, click **Save** to store it, or **Back to segments list** to abort the process.  
  You are returned to the **My segments** page and the new segment is added to the list.  

## Example  

To define a segment for all females over the age of 25, living in London, who have clicked on an email link in the last three months:

1. Click the **Segments** tab.  
  The **My segments** page displays.  
2. Click **Create new segment**.  
  The **New segment** page displays.  
1. Select the system generated segment name and enter one of your choice.  
2. Click **Create demographic rule**.  
  The **Create demographic rule** page displays.  
2. Click **Create custom rule**.  
  The **Demographic custom rule** page displays.  
1. Select the system generated custom rule name and enter one of your choice.  
2. Under **Match**, select **ALL**.  
3. Under **Gender**, select **Equal to** in the first box, then **F** in the second box.  
4. Under **Add condition**, select **Birthday date**, then:  
  - In the first box, select **Greater than**  
  - In the second box, enter **01/01/1991**  
4. Under **Add condition**, select **City**, then:  
  - In the first box, select **Equal to**  
  - In the second box, enter **London**  
4. Click **Add** to save the demographic rule.  
  You are returned to the **New segment** page  
2. Click **Create digital messages rule**.  
  The **Create digital messages rule** page displays.  
2. Click **Create custom rule**.  
  The **Digital messages custom rule** page displays.  
1. Select the system generated custom rule name and enter one of your choice.  
2. Under **Match**, select **ALL**.  
3. Under **Action**, select **Have clicked**.  
4. Under **Time frame**:  
  - Select the **In the last...** radio button  
  - Enter **3** in the first box  
  - Click the downwards pointing arrow to the right of the second box, and select **months**  
4. Click **Add** to save the digital messages rule.  
  You are returned to the **New segment** page  
4. Click **Save** to save the new segment.  
  You are returned to the **My segments** page  

***Next page:***  
[Creating a demographic rule](CreatingDemographicRule.md)  

----------

## Related Pages:  

- [Managing segments](ManagingSegments.md)  
  - [Viewing segments](ViewingSegments.md)  
  - [Segment details](SegmentDetails.md)  
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
