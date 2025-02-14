# TocPr

Table of contents properties.

## Type

Object

## Properties

| Name | Type | Description |
| ---- | ---- | ----------- |
| ShowPageNums | boolean | Specifies whether to show page numbers in the table of contents. |
| RightAlgn | boolean | Specifies whether to right-align page numbers in the table of contents. |
| LeaderType | [TocLeader](../Enumeration/TocLeader.md) | The leader type in the table of contents. |
| FormatAsLinks | boolean | Specifies whether to format the table of contents as links. |
| BuildFrom | [TocBuildFromPr](../Enumeration/TocBuildFromPr.md) | Specifies whether to generate the table of contents from the outline levels or the specified styles. |
| TocStyle | [TocStyle](../Enumeration/TocStyle.md) | The table of contents style type. |


## Example

This example adds a table of contents with the specified properties to the document.

```javascript
let tocPr = {"ShowPageNums": true, "RightAlgn": true, "LeaderType": "dot", "FormatAsLinks": true, "BuildFrom": {"OutlineLvls": 9}, "TocStyle": "standard"};
doc.AddTableOfContents(tocPr);
```
