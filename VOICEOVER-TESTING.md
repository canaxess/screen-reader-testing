# VoiceOver (iOS 14.6)
Understand the core gestures for navigating VoiceOver on iOS with the [mobile testing guide Android & iOS from The Paciello Group](https://www.tpgi.com/mobile-accessibility/). Testing based in part on the BBC News Accessibility document [Accessibility and Testing with VoiceOver iOS (iPhone/iPad)](https://bbc.github.io/accessibility-news-and-you/accessibility-and-testing-with-voiceover-ios).

## Screen reader tests
1. `Ensure the screen reader output matches the visual output of all headings`
1. `Ensure the screen reader output matches the visual output of all links (as a minimum)`
1. `Ensure the screen reader output matches the visual output of all list elements`
1. `Ensure the screen reader output the first 2 rows of a table and announces the columns`
1. `Ensure the screen reader output every visual error message`
1. `Ensure the screen reader output all significant page activity (ajax spinner icon, new page)`
1. `Ensure the screen reader output a controls outcome (collapsed/expanded, x number of items returned)`

## Add the accessibility shortcut
1.	Enabled this by going to **Settings** / **Accessibility** / **Accessibility Shortcut**
2.	Select **VoiceOver**

> The accessibility shortcut makes testing a lot quicker and easier as you don't have to go into settings each time to switch VoiceOver on and off.

## Add the Rotor actions
1.	Enabled these by going to **Settings** / **Accessibility** / **VoiceOver** / **Rotor**
2.	Select **Headings**, **Links**, **Form Controls**, **Tables**, **Lists**, **Landmarks**

> The Rotor is a virtual control built into VoiceOver. It allows you to select how you navigate through a dial format that lists marked-up elements on screen. It works with web content as well as native apps

## General
1.	Open Safari
2.	Go to the testing URL
3.	Turn VoiceOver on by triple clicking the home button
4.	Turn VoiceOver off by triple clicking the home button when testing has finished

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
