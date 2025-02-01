# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle but common error in JavaScript when interacting with the DOM. The bug involves a simple typo in the `getElementById` method, leading to unexpected behavior.

## Bug Description
The bug is a typographical error in the JavaScript code that attempts to access an HTML element using its ID.  Instead of using the correct `document.getElementById('myDiv')`, the code uses `document.getElementByIdx('myDiv')`, which results in a runtime error in most browsers.

## Bug Reproduction
1. Open `bug.html` in a web browser.
2. Observe that the text within the div with id "myDiv" does not change, and an error occurs in your console.

## Solution
The solution simply corrects the typo in the JavaScript code. The corrected code can be found in `bugSolution.html`.