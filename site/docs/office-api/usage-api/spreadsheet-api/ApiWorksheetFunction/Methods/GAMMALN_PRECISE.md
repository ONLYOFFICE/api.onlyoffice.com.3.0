# GAMMALN_PRECISE

Returns the natural logarithm of the gamma function.

## Syntax

```javascript
expression.GAMMALN_PRECISE(arg1);
```

`expression` - A variable that represents a [ApiWorksheetFunction](../ApiWorksheetFunction.md) class.

## Parameters

| **Name** | **Required/Optional** | **Data type** | **Default** | **Description** |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| arg1 | Required | [ApiRange](../../ApiRange/ApiRange.md) | [ApiName](../../ApiName/ApiName.md) | number |  | The value for which the natural logarithm of the gamma function will be calculated, a positive number. |

## Returns

number

## Example



```javascript
var oWorksheet = Api.GetActiveSheet();
var oFunction = Api.GetWorksheetFunction();
var ans = oFunction.GAMMALN_PRECISE(0.5);
oWorksheet.GetRange("B2").SetValue(ans);


```
