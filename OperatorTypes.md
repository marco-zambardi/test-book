# Operator types

Contactplan provides the following operator types to apply search criteria to condition attributes:  

- Equal to  
- Like  
- Not equal to  
- Greater than  
- Less than  
- Equal to or greater than  
- Equal to or less than  
- Is null  
- Is not null  

See [Data types](DataTypes.md) and [Input field types](InputFieldTypes.md) for more about each data type and input field mentioned in the following sections.  

## Equal to  

The **Equal to** operator is used to select all those contacts that exactly match the value entered in the condition input field.  

**Example:**  

Setting the *First Name* condition to **Equal to**, with *Sam* as the input field value, selects all those contacts whose first name is exactly *Sam*. Contacts whose first name is, for example, Samantha or Sammy are not selected.  

The **Equal to** operator applies to **string**, **numeric** and **date** data types.  

**Note:**  
The **Equal to** operator can also be applied when multiple values are set for a given attribute. It is used to select those contacts for which the relevant attribute has a value that exactly matches at least one of those entered in the condition input field. In this instance, the **Equal to** operator applies to **string** data types only.  

## Like  

The **Like** operator is used to select all those contacts for which the relevant attribute partially matches the value entered in the condition input field. This means that the operator implicitly uses wildcards to match the input field with the relevant attribute values in the database.  

**Example:**  

Setting the *First Name* condition to **Like**, with *Sam* as the input field value, selects all those contacts whose first name has *Sam* as any part of their name. Contacts whose first name is, for example, Sam, Samantha or Sammy are selected.  

The **Like** operator applies to **string** data types.  

## Not equal to  

The **Not equal to** operator is used to select all those contacts that do not match the value entered in the condition input field.  

**Example:**  

Setting the *First Name* condition to **Not equal to**, with *Sam* as the input field value, selects all those contacts whose first name is not *Sam*. Contacts whose first name is, for example, Samantha, Sammy, Paul, John and so on, are selected.  

The **Not equal to** operator applies to **string**, **numeric** and **date** data types.  

**Note:**  
The **Not equal to** operator can also be applied when multiple values are set for a given attribute. It is used to select those contacts for which the relevant attribute value does not match any of those entered in the condition input field. In this instance, the **Not equal to** operator applies to **string** data types only.  

## Greater than  

The **Greater than** operator applies to attributes that can be ordered. It is used to select those contacts for which the relevant attribute has a value greater than the one entered in the condition input field.  

**Example:**  

Setting the *Number of children* condition to **Greater than**, with *3* as the input field value, selects all contacts with 4, 5, 6 or more children, but does not select those with 3 or less children.  

The **Greater than** operator applies to **numeric** and **date** data types.  

## Less than  

The **Less than** operator applies to attributes that can be ordered. It is used to select those contacts for which the relevant attribute has a value less than the one entered in the condition input field.  

**Example:**  

Setting the *Number of children* condition to **Less than**, with *3* as the input field value, selects all contacts with 0, 1 or 2 children, but does not select those with 3 or more children.  

The **Less than** operator applies to **numeric** and **date** data types.  

## Equal to or greater than  

The **Equal to or greater than** operator applies to attributes that can be ordered. It is used to select those contacts for which the relevant attribute has a value equal to or greater than the one entered in the condition input field.  

**Example:**  

Setting the *Number of children* condition to **Equal to or greater than**, with *3* as the input field value, selects all contacts with 3, 4, 5 or more children, but does not select those with 2 or less children.  

The **Equal to or greater than** operator applies to **numeric** and **date** data types.  

## Equal to or less than  

The **Equal to or less than** operator applies to attributes that can be ordered. It is used to select those contacts for which the relevant attribute has a value equal to or less than the one entered in the condition input field.  

**Example:**  

Setting the *Number of children* condition to **Equal to or less than**, with *3* as the input field value, selects all contacts with 0, 1, 2 or 3 children, but does not select those with 4 or more children.  

The **Equal to or less than** operator applies to **numeric** and **date** data types.  

## Is null  

The **Is null** operator is used to select all those contacts that have no value entered for the relevant attribute in the database. If this operator is selected, no value is required in condition input field.  

**Example:**  

Setting the *Gender* condition to **Is null**, selects all those contacts that do not have gender information in the database.  

The **Is null** operator applies to **string**, **numeric** and **date** data types.  

## Is not null  

The **Is not null** operator is used to select all those contacts that have anything but no value entered for the relevant attribute. This means all contacts that have any value for the relevant attribute in the database are selected. If this operator is selected, no value is required in condition input field.  

**Example:**  

Setting the *Gender* condition to **Is not null**, selects all those contacts that have any gender information in the database.  

The **Is not null** operator applies to **string**, **numeric** and **date** data types.  

***Next page:***  
[Understanding contactplan](UnderstandingContactPlan.md)  

----------

## Related Pages:  

- [Data types, input fields and operators](InputBoxOperators.md)  
  - [Data types](DataTypes.md)  
  - [Input field types](InputFieldTypes.md)  
- [Managing segments](ManagingSegments.md)  
- [Managing plans](ManagingPlans.md)  

### Also see:  

- [Managing reports]  
- [Managing settings](ManagingSettings.md)  
  - [Segmentation settings]  
  - [Local settings](LocalSettings.md)  
  - [Managing DND policy settings](ManagingDND.md)  
  - [Managing users]  

### Other links:  

- [ContactLab contactplan](Home.md)  
- [Glossary]  
