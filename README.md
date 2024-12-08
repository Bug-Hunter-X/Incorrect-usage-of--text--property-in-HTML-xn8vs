# Incorrect Usage of 'text' Property in HTML

This repository demonstrates a subtle error that can occur when manipulating text content within HTML elements using JavaScript.  The example showcases the improper use of the 'text' property and provides the correct approach using 'textContent' or 'innerText'.

## Bug Description
Attempting to directly set the 'text' property of an HTML element's text node will result in a TypeError in most browsers. This is because 'text' is not a standard property for directly manipulating the text content of elements.  The solution shows the correct and supported methods.

## Solution
To correctly modify the text content of HTML elements use either 'textContent' or 'innerText'.  The difference between the two lies primarily in how they handle HTML within the text; 'innerText' renders the HTML, while 'textContent' treats it as plain text.