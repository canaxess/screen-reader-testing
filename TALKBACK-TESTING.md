# TalkBack v9.1 & v12.5
>- (Galaxy Tab A7 Android v10 TalkBack v9.1)
>- (Galaxy Note 10+ Android v11 TalkBack v12.5)

<a href="https://govau.github.io/accessibility/calibrate.html">Calibration page</a>

## Screen reader tests
1. `Ensure the screen reader output matches the visual output of all headings`
1. `Ensure the screen reader output matches the visual output of all links (as a minimum)`
1. `Ensure the screen reader output matches the visual output of all list elements`
1. `Ensure the screen reader output the first 2 rows of a table and announces the columns`
1. `Ensure the screen reader output every visual error message`
1. `Ensure the screen reader output all significant page activity (ajax spinner icon, new page)`
1. `Ensure the screen reader output a controls outcome (collapsed/expanded, x number of items returned)`

## Add the accessibility shortcut
> (Galaxy Tab A7 Android v10 TalkBack v9.1)
1.	Enabled this by going to **Settings** / **Accessibility** / **Advanced Settings** / **Volume up and down keys** / **Selected Service**
2.	Select **TalkBack**
3.	Select **On**

> (Galaxy Note 10+ Android v11 TalkBack v12.5)
1. Enabled this by going to **Settings** / **Accessibility** / **TalkBack**
2. Toggle **TalkBack Shortcut** on
3. Hold **Volume Inc/Dec** together for 3 seconds to enable/disable TalkBack

The accessibility shortcut makes testing a lot quicker and easier as you don't have to go into settings each time to switch VoiceOver on and off.

## Customise the reading options
1.	Enabled these by going to **Settings** / **Accessibility** / **Accessibility** / **Installed services** / **TalkBack** / **Settings** / **Customise TalkBack menu** / **Edit navigation options**
2.	Select **Headings**, **Controls**, **Links**, **Landmarks**, **Special content**, **Other web navigation**

## General
> (Galaxy Note 10+ Android v11 TalkBack v12.5)
1.	Open Chrome/Firefox
2.	Go to the testing URL
3.	Turn TalkBack on by holding Volume buttons for 3 seconds and do the same to turn off when testing has finished

## Test Headings
> (Galaxy Note 10+ Android v11 TalkBack v12.5)
1.	With TalkBack on, swipe to the right on the screen with three fingers and select **Headings** from the options
2.	Swipe through the page headings(Swipe to right with one finger to read next **Heading** and swipe to left read previous **Heading**)
3.	TEST : `Ensure the screen reader output matches the visual output of all headings`

> (Galaxy Tab A7 Android v10 TalkBack v9.1)
1.	With TalkBack on, swipe up then to the right wtih a single finger and select **Navigation** from the options
2.	Select **Headings**
3.	Swip through the page headings
3.	TEST : `Ensure the screen reader output matches the visual output of all headings`

## Test Links
> (Galaxy Note 10+ Android v11 TalkBack v12.5)
1.	With TalkBack on, swipe to the right on the screen with three fingers and select **Links** from the options
2.	Swipe through the page links(Swipe to right with one finger to read next **Link** and swipe to left read previous **Link**)
3.	TEST : `Ensure the screen reader output matches the visual output of all links (as a minimum)`

## Test Error Messages
1. Trigger all form errors
2. TEST : `Ensure the screen reader output every visual error message` without swiping

## Test Screen Activity
1. Trigger significant screen change (only relevant for Single Page Applications)
2. TEST : `Ensure the screen reader output all significant page activity (ajax spinner icon etc)`

## Test Lists and Tables
A manual read through of each element is required as TalkBack doesn't provide an easy way to navigate through Tables and Lists. 

