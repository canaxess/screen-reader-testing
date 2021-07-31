# VoiceOver (macOS 11.1 Big Sur)
Understand the core gestures for navigating VoiceOver on macOS with the [macOS keyboard shortcuts](https://dequeuniversity.com/screenreaders/voiceover-keyboard-shortcuts).

## Screen reader tests
1. `Ensure the screen reader output matches the visual output of all headings`
1. `Ensure the screen reader output matches the visual output of all links (as a minimum)`
1. `Ensure the screen reader output matches the visual output of all list elements`
1. `Ensure the screen reader output the first 2 rows of a table and announces the columns`
1. `Ensure the screen reader output every visual error message`
1. `Ensure the screen reader output all significant page activity (ajax spinner icon, new page)`
1. `Ensure the screen reader output a controls outcome (collapsed/expanded, x number of items returned)`

## Add the accessibility shortcut
1.	Enable this by going to **System Preferences** / **Keyboard** / **Shortcuts** / **Accessibility**
2.	Select **Turn VoiceOver on or off**

> The accessibility shortcut makes testing a lot quicker and easier as you don't have to go into settings each time to switch VoiceOver on and off.

## Enable keyboard accessibility on macOS
1.	Go to **System Preferences** / **Keyboard** / **Shortcuts**
2.	Select **Use keyboard navigation to move focus between controls**

## Enable keyboard accessibility in Safari
1.  Open Safari
1.	Go to **Preferences** / **Advanced**
2.	Select **Press Tab to highlight each item on a webpage**

## General
1.	Open Safari
2.	Go to the testing URL
3.	Turn VoiceOver on by pressing <kbd>command</kbd> + <kbd>F5</kbd>
4.	Turn VoiceOver lock on by pressing <kbd>control</kbd> + <kbd>option</kbd> + <kbd>;</kbd>
5.	Turn VoiceOver off by pressing <kbd>;</kbd> followed by <kbd>command</kbd> + <kbd>F5</kbd>

## Test Headings
1. Press <kbd>Command</kbd> + <kbd>H</kbd> to move forward through all headings, <kbd>Shift</kbd> + <kbd>Command</kbd> + <kbd>H</kbd> to move backward through all headings
3.	TEST : `Ensure the screen reader output matches the visual output of all headings`

## Test Links
1. Press <kbd>Command</kbd> + <kbd>L</kbd> to move forward through all links, <kbd>Shift</kbd> + <kbd>Command</kbd> + <kbd>L</kbd> to move backward through all links
3.	TEST : `Ensure the screen reader output matches the visual output of all links (as a minimum)`

## Test Lists

1. Press <kbd>Command</kbd> + <kbd>X</kbd> to move forward through all lists, <kbd>Shift</kbd> + <kbd>Command</kbd> + <kbd>X</kbd> to move backward through all lists
3.	TEST : `Ensure the screen reader output matches the visual output of all list elements`

## Test Tables

1.	Press <kbd>Command</kbd> + <kbd>T</kbd> to move forward through all tables, <kbd>Shift</kbd> + <kbd>Command</kbd> + <kbd>T</kbd> to move backward through all tables
2.	Within each table press <kbd>Right Arrow</kbd> to move forward through the cells, press <kbd>Left Arrow</kbd> to move backward through the cells
4.	TEST : `Ensure the screen reader output the first 2 rows of a table and announces each column`

## Test Error Messages

1. Trigger all form errors
2. TEST : `Ensure the screen reader output every visual error message`

## Test Screen Activity

1. Trigger significant screen change (only relevant for Single Page Applications)
2. TEST : `Ensure the screen reader output all significant page activity (ajax spinner icon etc)`
