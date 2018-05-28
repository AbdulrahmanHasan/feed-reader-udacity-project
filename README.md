# Feed Reader Testing

## Steps to run application

To start the app, open index.html in your browser.

The tests were written in the feedreader.js file. The test results
appears at the bottom of the index.html page.

Tests that are green have passed and red have failed.

### The tests:

1) tests to make sure that the all Feeds variable has been defined and that it is not empty.
2) loops through each feed and determines if the URL is defined and not empty.
3) loops through each feed and determines that each feed has a name and not empty.
4) ensures the menu element is hidden by default.
5) validates proper functioning of the hamburger menu toggle.
6) tests that there is at least one entry in feed.
7) tests that new content is loaded by loadFeed().
