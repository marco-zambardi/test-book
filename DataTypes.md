# Data types

<<<<<<< HEAD
Contactplan handles the following main types of data:  

- String  
- Numeric  
- Date  

See [Operator types](OperatorTypes.md) and [Input field types](InputFieldTypes.md) for more about each operator type and input field mentioned in the following sections.  

## String  

Attributes with a data type equal to *string* have alpha-numeric values that can be made up of more than on word. For example, the **store name** attribute can have value such as **N.5 mall**.  

- Permissible operators:  
  - Equal  
  - Like  
  - Not equal  
  - Is null  
  - Is not null  
- Permissible input fields:  
  - Checkbox  
  - Multiple options  
  - Autocomplete  
  - Free text  
  - Drill down  

**Note:**  
The actual operators that are available depends upon the input field type that is set for the attribute.  

## Numeric  

Attributes with a data type equal to *numeric* can only have numeric values, whether they are integers, long integers, floats, real, or similar. For example, the **number of purchase** attribute can have a value such as 1,2,3..., while the **item in the order** attribute can have a value such as 1,2,3..., or -1,-2..., in the case of returns.  

- Permissible operators:  
  - Equal  
  - Not equal  
  - Greater than  
  - Less than  
  - Equal to or greater than  
  - Equal to or less than  
  - Between  
  - Is null  
  - Is not null  
- Permissible input fields:  
  - Checkbox  
  - Multiple options  
  - Number  

**Note:**  
The actual operators that are available depends upon the input field type that is set for the attribute.  

## Date  

Attributes with a data type equal to *date* have a value that uses the DD/MM/YYYY format.  

- Permissible operators:  
  - Equal  
  - Not equal  
  - Greater than  
  - Less than  
  - Equal to or greater than  
  - Equal to or less than  
  - Between  
  - Is null  
  - Is not null  
- Permissible input fields:  
  - Calendar  

**Note**  
When expressing conditions for attributes with a data type equal to *date*, the following applies:  

- Greater than = After the specified date  
- Less than = Before the specified date  
- Between = Within the time frame specified by the two dates  

***Next page:***  
[Input field types](InputFieldTypes.md)  

----------

## Related Pages:  

- [Data types, input fields and operators](InputBoxOperators.md)  
  - [Input field types](InputFieldTypes.md)  
  - [Operator types](OperatorTypes.md)  
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
=======
>>>>>>> 7da6563867e212c55108eafb8489928e5cfa34aa