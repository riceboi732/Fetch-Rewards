# Fetch-Rewards

This is the take home coding assignment from Fetch Reward for the role of iOS Engineer. While this submission does indeed use a decent amount of UIKit for the UI creation/design, I am very enthusiastic to learn SwiftUI and switch to the dark (and honestly more code friendly) side of iOS engineering!

## Assumptions

As noted in the assignment prompt, there is an emphasis on removing and filtering out null and empty values from the API before displaying. As such, in the case where a JSON request is missing, the entry is not shown and skipped (as opposed to an empty cell)

## Potential Updates

Given the one-week deadline limit of the assignment, while the app works and I wasn't able to "break" it during a rudimentary QA process (general "bad user" testing on a simulated app on the latest version of Xcode) the app heavily emphasizes functionality and robustness over user-friendliness. Given more time, here are some of the things I would have liked to take a closer look at and seek to improve.
- While clearly displayed, instructions for each recipe can prove to be hard to read as they can be in a paragraph format that makes the step-by-step aspect of instructions moot
- The app is built in an environment where wifi is assumed, when testing the app with the wifi turned off, the app crashed and does not function as expected. Given more time, there could be some more time and effort put into the user interface in the case of no wifi or wifi interruption (perhaps a display mentioning there is no wifi or that there are network issues at the moment)
