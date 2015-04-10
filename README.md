# jQuery.dragmove
Lightweight jQuery extension for enabling draggable functionality on DOM elements without requiring the `jQuery UI` library. Compatible with trackpads, touch devices, and standard computer mice.

## Installation
Include the latest version of [jQuery](http://jquery.com/download) and `jQuery.dragmove.js` in the `<head>` of your HTML document:
```html
<script src="jQuery.min.js"></script>  
<script src="jQuery.dragmove.js"></script>
```
## How to Use
Start by calling the `dragmove()` method on any element. Optionally add inertia by declaring a CSS `transition` on the element. The following example will enable dragging functionality for all `div` elements. See the live demo: [code.nath.co/dragmove](http://code.nath.co/dragmove)

**jQuery**
```javascript
$(function() {  

    // All div elements
    $('div').dragmove(); 

});
```

**CSS ( Optional )**
```css
div {
    -webkit-transition: all 200ms ease-out;
    -moz-transition: all 200ms ease-out;
    -o-transition: all 200ms ease-out;
    transition: all 200ms ease-out;
}  
```  

## Browser Support
– Google Chrome  
– Safari ( Desktop and Mobile )  
– Internet Explorer ( 8, 9, 10+ )  
– Firefox 

## Feedback
If you discover any issues or have questions regarding usage, please send a message to [code@nath.co](mailto:code@nath.co) or find me on GitHub [@nathco](https://github.com/nathco).