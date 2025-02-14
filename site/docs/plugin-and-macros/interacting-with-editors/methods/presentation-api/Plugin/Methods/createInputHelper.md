# createInputHelper

Defines the method used to create an &#123;@link inputhelper input helper&#125; - a window that appears and disappears when you type text. Its location is tied to the cursor.

## Syntax

```javascript
expression.createInputHelper();
```

`expression` - A variable that represents a [Plugin](../Plugin.md) class.

## Parameters

This method doesn't have any parameters.

## Returns

This method doesn't return any data.

## Example

```javascript
window.Asc.plugin.init = function(text) {
    if (!window.isInit) {
        window.isInit = true;
        window.Asc.plugin.currentContentControl = null;
        window.Asc.plugin.createInputHelper();
        window.Asc.plugin.getInputHelper().createWindow();
    }
};
```
