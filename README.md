# Shopify Frontend Challenge 2021

My submission for Shopify's frontend coding challenge (Github Pages: cindy-wang328.github.io/shopifywebcodingchallenge1-21/)

Instructions: https://docs.google.com/document/d/1AZO0BZwn1Aogj4f3PDNe1mhq8pKsXZxtrG--EIbP_-w/edit

Assumptions: The instructions says "When they've selected 5 nominees they should be notified they're **finished**", so I did not allow them to nominate anything after there have been 5 nominated.

Extra features not in instructions:
- Included image from the API if it exists
- Saves both the last search and the nominated list in Local Storage so if page reloads they will still be there
- Button text changes to "Nominated" or "Max 5 nominations" when necessary
- Search result title changes to "No results for" and the error message, if there are no results
- Trims input because sometimes having too many blank spaces causes Movie not found
- Clear search and Remove all nominations buttons

Tools used:
- HTML, JS, jQuery because it is easy to set up and run on Github Pages (and to stackoverflow :D )
- Bootstrap for the styling because its grid layout is useful to display blocks of search results
(Also left api key in the code so it is easier to set up on github pages.. at my last co-op the keys were environment variables)

![Screenshot with 5 nominations](https://raw.githubusercontent.com/cindy-wang328/ShopifyWebCodingChallenge1-21/main/5_nominations_screenshot_new.png)

![Screenshot with 3 nominations](https://raw.githubusercontent.com/cindy-wang328/ShopifyWebCodingChallenge1-21/main/2nd_screenshot.png)

