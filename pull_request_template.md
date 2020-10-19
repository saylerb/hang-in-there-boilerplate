## Feature Description
>Clearly and concisely describe the feature.

Refactored innerHTML in order to get saved posters to show up. Show saved posters button now shows all of the saved posters.

## Analysis and Design
>Analyze and attach the design documentation, if any.

N/A

## Solution Description
>Describe your code changes in detail for reviewers.

Used innerHTML to insert same structure of main poster into the poster grid to allow for mini poster to appear.
By assigning savedPostersGrid to an empty string and using += operator to add each innerHTML insertion, we were able to get all the saved posters to show up.

## Output screenshots
>Post the output screenshots, if an UI is affected or added due to this feature.

N/A
