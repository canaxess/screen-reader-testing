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
4.	Turn VoiceOver off by pressing <kbd>command</kbd> + <kbd>F5</kbd>

## Test Headings
1.	Select from the Rotor **Headings**
2.	Swipe through the page headings
3.	TEST : `Ensure the screen reader output matches the visual output of all headings`

## Test Links
1.	Select from the Rotor **Links**
2.	Swipe through the page links
3.	TEST : `Ensure the screen reader output matches the visual output of all links (as a minimum)`

## Test Lists

1.	Select from the Rotor **Lists**
2.	Swipe through the page lists
3.	TEST : `Ensure the screen reader output matches the visual output of all list elements`

## Test Tables

1.	Select from the Rotor **Tables**
2.	Swipe through the page tables
3.	TEST : `Ensure the screen reader output the first 2 rows of a table and announces each column`

## Test Error Messages

1. Trigger all form errors
2. TEST : `Ensure the screen reader output every visual error message` without swiping

## Test Screen Activity

1. Trigger significant screen change (only relevant for Single Page Applications)
2. TEST : `Ensure the screen reader output all significant page activity (ajax spinner icon etc)`
