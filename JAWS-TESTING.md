# JAWS (v2021) - Work in Progress
Understand the core navigation methods for JAWS with the [JAWS keyboard shortcuts](https://dequeuniversity.com/screenreaders/jaws-keyboard-shortcuts). 

## Screen reader tests
1. `Ensure the screen reader output matches the visual output of all headings`
1. `Ensure the screen reader output matches the visual output of all links (as a minimum)`
1. `Ensure the screen reader output matches the visual output of all list elements`
1. `Ensure the screen reader output the first 2 rows of a table and announces the columns`
1. `Ensure the screen reader output every visual error message`
1. `Ensure the screen reader output all significant page activity (ajax spinner icon, new page)`
1. `Ensure the screen reader output a controls outcome (collapsed/expanded, x number of items returned)`

## General
1.	Open Chrome
2.	Go to the testing URL
3.	Start JAWS
4.	Exit JAWS when testing has completed

## Test Headings
1.	Press <kbd>H</kbd> to move forward through all headings, <kbd>Shift</kbd> + <kbd>H</kbd> to move backward through all headings
3.	TEST : `Ensure the screen reader output matches the visual output of all headings`

## Test Links
1.	Press <kbd>Tab</kbd> to move forward through all focusable items, <kbd>Shift</kbd> + <kbd>Tab</kbd> to move backward through all focusable items
3.	TEST : `Ensure the screen reader output matches the visual output of all links (as a minimum)`

## Test Lists

1.	Press <kbd>L</kbd> to move forward through all lists, <kbd>Shift</kbd> + <kbd>L</kbd> to move backward through all lists
2.  Within each list Press <kbd>I</kbd> to move forward through all list items, <kbd>Shift</kbd> + <kbd>I</kbd> to move backward through all list items
3.	TEST : `Ensure the screen reader output matches the visual output of all list elements`

-- WIP --

## Test Tables

1.	Press <kbd>T</kbd> to move forward through all tables, <kbd>Shift</kbd> + <kbd>T</kbd> to move backward through all tables
2.	Within each table press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Right Arrow</kbd> to move forward through the cells, press <kbd>Up Arrow</kbd> to move backward through the cells
4.	TEST : `Ensure the screen reader output the first 2 rows of a table and announces each column`

## Test Error Messages

1. Trigger all form errors
2. TEST : `Ensure the screen reader output every visual error message` without swiping

## Test Screen Activity

1. Trigger significant screen change (only relevant for Single Page Applications)
2. TEST : `Ensure the screen reader output all significant page activity (ajax spinner icon etc)`
