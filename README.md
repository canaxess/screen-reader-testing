# Screen reader testing
Move beyond trivial screen reader testing and instead test an entire workflow. Can a user navigate and traverse several workflows to complete a task?

7 tests in total with the first 4 navigational waypoints a user may encounter traversing a workflow, followed by 3 tests interacting with elements as part of the workflow.

## Orientation and waypoint finding
1. `Ensure the screen reader output matches the visual output of all headings`
1. `Ensure the screen reader output matches the visual output of all links (as a minimum)`
1. `Ensure the screen reader output matches the visual output of all list elements`
1. `Ensure the screen reader output the first 2 rows of a table and announces the columns`

## User actions and workflow traversal
5. `Ensure the screen reader output every visual error message`
6. `Ensure the screen reader output all significant page activity (ajax spinner icon, new page)`
7. `Ensure the screen reader output a controls outcome (collapsed/expanded, x number of items returned)`

## Screen reader documentation
- Testing with [NVDA (v2020)](https://github.com/canaxess/accessibility-resources/blob/main/NVDA-TESTING.md)
- Testing with [JAWS (v2021)](https://github.com/canaxess/accessibility-resources/blob/main/JAWS-TESTING.md)
- Testing with [VoiceOver (iOS 14.6)](https://github.com/canaxess/accessibility-resources/blob/main/VOICEOVER-TESTING.md)
- Testing with [VoiceOver (macOS 11.1 Big Sur)](https://github.com/canaxess/accessibility-resources/blob/main/VOICEOVER-MACOS-TESTING.md)
- Testing with [TalkBack (Android v10, Android v11)](https://github.com/canaxess/accessibility-resources/blob/main/TALKBACK-TESTING.md)
