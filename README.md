# CSS ':checked' Pseudo-class Selector Issue

This repository demonstrates a subtle bug in CSS where an unexpected space before the opening curly brace of a ':checked' selector prevents it from functioning correctly.

## Bug Description

The ':checked' pseudo-class selector is used to style elements when a checkbox is checked.  However, if a space is inserted before the opening curly brace, the styles are not applied.

## Reproduction Steps

1. Clone this repository.
2. Open `bug.css` and observe the incorrect styling.  
3. Open `bugSolution.css` and observe the corrected styling (no extra space).

## Solution

Remove any spaces between the selector and the opening curly brace.