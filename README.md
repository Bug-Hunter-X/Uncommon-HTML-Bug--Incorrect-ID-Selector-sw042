# Uncommon HTML Bug: Incorrect ID Selector

This repository demonstrates a common error related to using special characters within the ID attribute of an HTML element and how to resolve it.  Incorrectly using special characters in IDs can lead to unexpected behavior and prevent JavaScript from properly accessing elements.

## Bug Description

The bug is found in `bug.html`.  JavaScript attempts to select an element with an ID containing a '#' character. HTML IDs cannot contain special characters like '#' directly. This will cause an error because `document.getElementById()` won't find the element.

## Solution

The solution is provided in `bugSolution.html`. The ID is corrected to use only valid characters and the javascript code is updated to correctly access the updated element ID. 
