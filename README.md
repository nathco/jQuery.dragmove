# jQuery.dragmove
Lightweight jQuery extension for enabling draggable functionality on DOM elements without requiring the `jQuery UI` library. Compatible with trackpads, touch devices, and standard computer mice.

## Installation
Include the latest version of [jQuery](http://jquery.com/download) and `jQuery.dragmove.js` in the `<head>` of your HTML document:
```html
<script src="jQuery.min.js"></script>  
<script src="jQuery.dragmove.js"></script>
```
## How to Use
Start by calling the `dragmove();` method on any DOM element. Move the element by clicking ( tapping on touch devices ) and dragging it around the viewport. The following example will enable dragging functionality for all `div` elements.

```javascript
$(function() {  

    // All div elements
    $('div').dragmove(); 
	
});
```

**Live Demo:** [code.nath.co/dragmove](http://code.nath.co/dragmove)

## Browser Support
– Google Chrome  
– Safari ( Desktop and Mobile )  
– Internet Explorer ( 9, 10, 11 )  
– Firefox 

## Feedback
If you discover any issues or have questions regarding usage, please send a message to [mail@nath.co](mailto:mail@nath.co) or find me on twitter [@NathanRutzky](http://twitter.com/NathanRutzky).