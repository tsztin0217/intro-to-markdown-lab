# Anatomy of a CSS Selector
![banner-cat-on-laptop](https://images.unsplash.com/photo-1634838037553-66f5ce322212?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

## How does it work?
### Structure:
``` css
selector {
    property1: value;
    property2; value;
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
| **Selector** | The HTML element's name to be styled. <br> *Examples*: `<body>`, `<main>`, `<div>`, `<span>`|
| **Declaration** | The property-value pair. <br>*Examples*: `color: red`, `font-family: sans-serif`|
| **Properties** | The element(s) of the HTML element to be styled, such as color, font family, font size, etc. <br> *Examples*: `color`, `font-family`, `font-size` |
| **Property value** | Sepcifies the appearance to be assigned to the property. <br>*Examples*: `red`, `12px`, `sans-serif`|
> ***Additional notes on the syntax***: <br> All declaration must be wrapped in curly braces (`{}` ). *Colon (`:`)* is used for separating each property from its value, while *semicolon (`;`)*.

Reference: [CSS: Styling the content | MDN Docs](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Styling_the_content)