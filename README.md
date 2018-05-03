# Exercise
## Page events
With the button_event example, change the `btn.onclick` event to the other events listed below. Try to understand what's going on here. There are subtle differences between some of the events such as `window.onkeydown` and `window.onkeyup`.

Events for you to try:
* `btn.onfocus` and `btn.onblur` - The colour will change when the button is focused and unfocused (try pressing tab to tab on to the button and off again). These are often used to display information about how to fill in form fields when they are focused, or display an error message if a form field has just been filled in with an incorrect value.
* `btn.ondblclick` - The colour will change only when it is double-clicked.
* `btn.onmouseover` and `btn.onmouseout` - The colour will change when the mouse pointer is moved so it begins hovering over the button, or when it stops hovering over the button and moves off of it, respectively.
* `window.onkeydown`, `window.onkeyup` - The colour will change when a key is pressed on the keyboard.  Note that it doesn't work if you try to register this event handler on the button itself - we have to register it on the window object, which represents the entire browser window.
* `window.onload` - The colour will change once the page has finished loading. When we're running a page locally our page loads very fast so there's barely any delay between requesting the page and everything being loaded in. However, on the internet there can be a large delay depending on the size and complexity of the page.
