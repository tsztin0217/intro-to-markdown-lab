# Anatomy of a CSS Selector
![banner-cat-on-laptop](https://images.unsplash.com/photo-1634838037553-66f5ce322212?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

## How does it work?
### Structure:
``` css
selector {
    property1: value;
    property2: value;
}
```
### Example:
```css
p {
    color: red;
    font-family: sans-serif;
}
```
| Component | Description |
| --------- | ----------- |
| **Selector** | The HTML element to be styled. <br> *Examples*: `<body>`, `<main>`, `<div>`, `<span>`|
| **Declaration** | The property-value pair defining the style. <br>*Examples*: `color: red`, `font-family: sans-serif`|
| **Properties** | The aspects of the HTML element to be styled, such as color, font family, and font size. <br> *Examples*: `color`, `font-family`, `font-size` |
| **Property Value** | Specifies the style applied to the property. <br>*Examples*: `red`, `12px`, `sans-serif`|
#### ***Additional notes on syntax***: 
- All declarations must be wrapped in curly braces (`{}` ).
- *Colon (`:`)* separates each property from its value.
- *Semicolon (`;`)* is required at the end of each declaration.

Reference: [CSS: Styling the content | MDN Docs](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Styling_the_content)