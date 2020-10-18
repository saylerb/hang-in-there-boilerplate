## Feature Description
>Clearly and concisely describe the feature.

Takes input from image URL, title and quote to create and show as a new motivational poster.
As it accomplishes this it also toggles back to the main page to show the poster and prevents the default random poster to be shown.
Also cleaned up some code and added necessary semicolons.

## Analysis and Design
>Analyze and attach the design documentation, if any.

N/A

## Solution Description
>Describe your code changes in detail for reviewers.

Added a couple new functions.
The generatePoster function establishes through innerText the input values to the input boxes on the webpage.
It then passes them through into the Poster class.
Then by calling the showMyPoster the generatePoster function, event.preventDefault function and
hideForm function are all called initiating the input values to be formed as a customized poster.

## Output screenshots
>Post the output screenshots, if an UI is affected or added due to this feature.

N/A
