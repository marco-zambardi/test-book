# Input field types

The UI includes the following input field types:  

- Checkbox  
- Multiple options  
- Autocomplete  
- Free text  
- Drill down  
- Number  
- Calendar  

**Note:**  
Editable text boxes may be case-sensitive, depending upon the configuration settings that have been applied to your system.  

## Checkbox  

Checkbox input fields are used by default, for all attributes that have five different values or less stored in the database. For example, the **Gender** attribute has M and F checkboxes.  

### Use  

All available values for an attribute are shown and one or more can be selected, as appropriate. When more than one value is chosen, the condition selects all those contacts that satisfy at least one of the relevant values.  

**Example:**  

The **Store Category** attribute has *ecommerce*, *flagship store* and *mall* as possible values, to identify the type of store where a purchase has been made. If just *ecommerce* is selected, contactplan returns the contacts that have purchased at least once from an ecommerce store. If both *ecommerce* and *mall* are selected, contactplan returns the contacts that have purchased at least once from either an ecommerce store, or in a mall.  

## Multiple options  

 Multiple options input fields are used by default, for all attributes that have between five and 50 different values stored in the database.  

### Use  

The UI displays a selectable drop-down list showing the available values. A range of values are displayed and the remainder can be accessed by scrolling the list up or down.  

A single value can be selected by clicking it. The value is then highlighted. Further values can be added to the initial selection, by pressing CTRL and simultaneously clicking the additional values. The newly selected values are also highlighted.  

A previously selected value can be deselected, by pressing CTRL and simultaneously clicking the value. The value is no longer highlighted.  

When more than one value is chosen, the condition selects all those contacts that satisfy at least one of the relevant values.  

## Autocomplete  

Autocomplete input fields are used by default, for all attributes that have between 50 and 5000 different values stored in the database.  

### Use  

The UI displays an editable text box containing the word *Search*. When two or more characters are typed in the text box, contactplan automatically displays all of the available values that contain those characters, in a scrollable list. Click the required value to select it.  

When a value is chosen, the text box returns to its original state and the selected value is displayed beneath the box. Further values can be selected by repeating these steps.  

Once a value has been selected, it can be removed by clicking the associated **X** icon.  

When more than one value is chosen, the condition selects all those contacts that satisfy at least one of the relevant values.  

## Free text  

Free text input fields are used for all attributes that have several thousand different values stored in the database. Attributes such as **First name** or **Last name** typically have this type of input field.  

### Use  

The UI displays an editable text box containing the words *Type here*. Any required characters can be typed in the free text box, which are then used as the value for the condition. For example, for a **First name** attribute, type *John* to identify all contacts with that name.  

Only one value can be entered at a time, in this type of input field.  

***Tip:***  
If you need to define multiple values for an attribute with a free text input field, do the following:  

1. Select the required attribute again from the list in the **Add condition** panel.  
  A new condition for the appropriate attribute displays.  
2. Type the additional value for the attribute in the new free text box.  
3. Under **Match**, select **ALL** or **ANY** as required.  
  See [Understanding segmentation](UnderstandingSegmentation.md.md) for more details.  

## Drill down  

This special input field type may be used when there are attributes that are hierarchically related in a parent-child relationship. For example, when the possible values of one attribute depend upon the value selected for the parent attribute. Location-related attributes, such as **Continent**, **Country**, **Region** and **City** are typical examples of where this type of input field may be used.  

### Use  

The UI displays a selectable drop-down list showing the available values for the first-level attribute. A range of values are displayed and the remainder can be accessed by scrolling the list up or down. Do the following:  

- Click a first-level attribute value to select it.  
  A new drop-down list opens, which displays the appropriate second-level attribute values that are associated with the chosen first-level value.  
- Click a second-level attribute value to select it.  
  A new drop-down list opens, which displays the appropriate third-level attribute values that are associated with the chosen second-level value.  
- Repeat the above steps until attribute values have been selected for all levels of the drill down hierarchy.  

Only one value can be selected at a time for each level, in this type of input field.  

**Example:**  

For a geographic location-related condition:

- The first-level drop down list displays the continents: North America, South America, Africa, Europe, Asia and Australia  
- If Europe is selected, a second-level drop down list displays the countries: Spain, France, Italy, Portugal, Germany, Netherlands, Sweden, Norway and so on  
- If Italy is selected, a third-level drop down list displays the regions: Piedmont, Lombardy, Tuscany and so on  
- If Lombardy is selected, a fourth-level drop down list displays the cities: Milan, Bergamo, Monza and so on  

## Number  

Number input fields are only used for attributes that have a **Numeric** data type. See [Data types](DataTypes.md.md) for more details.  

### Use  

The UI displays a widget and a numeric value can either be typed in, or it can be selected by using the increase or decrease arrows provided.  

## Calendar  

Calendar input fields are only used for attributes that have a **Date** data type. See [Data types](DataTypes.md.md) for more details.  

A graphical calendar widget is provided that is used to select the required date.  

### Use  

The UI displays an editable text box containing the text *DD/MM/YYYY*. Do one of the following:  

- Click the text box to display the calendar widget  
  The widget shows one month at a time and opens at the current month.  
- Scroll the calendar forwards or backwards using the arrows provided, until the relevant month is displayed  
- Click the appropriate date in the calendar panel  
- The calendar widget closes and the selected date is displayed in the text box  
  or:  
- Type the desired date in the text box, using the DD/MM/YYYY format  

***Next page:***  
[Operator types](OperatorTypes.md.md)  

----------

## Related Pages:  

- [Data types, input fields and operators](InputBoxOperators.md.md)  
  - [Data types](DataTypes.md.md)  
  - [Operator types](OperatorTypes.md.md)  
- [Managing segments](ManagingSegments.md.md)  
- [Managing plans](ManagingPlans.md.md)  

### Also see:  

- [Managing reports]  
- [Managing settings](ManagingSettings.md.md)  
  - [Segmentation settings]  
  - [Local settings](LocalSettings.md.md)  
  - [Managing DND policy settings](ManagingDND.md.md)  
  - [Managing users]  

### Other links:  

- [ContactLab contactplan](Home.md.md)  
- [Glossary]  
