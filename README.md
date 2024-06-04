# To-Do List Application

This is a simple to-do list application built with HTML, CSS, and JavaScript.

## HTML

The HTML structure provides a user interface for the to-do list application. It includes input fields for entering a new task and its due date, a button for adding the new task to the to-do list, and an unordered list that will contain the to-do items. The HTML file also links to the CSS stylesheet for styling and the JavaScript file for functionality.

## CSS

The CSS file styles the HTML elements to give the to-do list application a clean and modern look. It uses flexbox for layout, making the application responsive. It also provides visual feedback to the user with hover effects.

## JavaScript

The JavaScript file provides the functionality for the to-do list application. It includes functions to handle the drop event during a drag-and-drop operation, to handle the end of a drag operation, and to add a new task to the list.

The `handleDrop(e)` function stops the event from bubbling up the DOM tree and swaps the HTML content of the source and target elements if they are not the same.

The `handleDragEnd(e)` function resets the opacity of the draggable element and removes the 'over' class from all items.

The `addtask()` function gets the values of the task and due date input fields, creates a new list item with these values and a checkmark, and adds it to the list. It also adds event listeners to the list item to toggle the 'done' class when it's clicked and to remove it from the list when it's double-clicked. After the list item is added to the list, the input fields are cleared.

The "Add Task" button has an event listener that calls the `addtask` function when it's clicked.
