# TextFormPrBase

Specific text field properties.

## Type

Object

## Properties

| Name | Type | Description |
| ---- | ---- | ----------- |
| comb | boolean | Specifies if the text field should be a comb of characters with the same cell width. The maximum number of characters must be set to a positive value. |
| maxCharacters | number | The maximum number of characters in the text field. |
| cellWidth | number | The cell width for each character measured in millimeters. If this parameter is not specified or equal to 0 or less, then the width will be set automatically. |
| multiLine | boolean | Specifies if the current fixed size text field is multiline or not. |
| autoFit | boolean | Specifies if the text field content should be autofit, i.e. whether the font size adjusts to the size of the fixed size form. |


## Example

This example creates a text form with the specific text form properties.

```javascript
let textFormPrBase = {"comb": true, "maxCharacters": 10, "cellWidth": 3, "multiLine": false, "autoFit": false};
let textForm = Api.CreateTextForm(textFormPrBase);
```
