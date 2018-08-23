 Feed-Reader-Testing-FEND Udacity Project
 
This project used a testing suite which is Jasmine, to validate my code. Udacity provided a starter code and required to write test spec in Jasmine.

Steps to run application

To start the app, open feedreader.html in your browser.

The tests were written in the feedreader.js file. The test results appears at the bottom of the index.html page.

Tests that are green have passed and red have failed.

The tests:

1.Tests to make sure that the allFeeds variable has been defined and that it is not empty.
2.Loops through each feed and determines if the URL is defined and not empty.
3.Loops through each feed and determines that each feed has a name and not empty.
4.Ensures the menu element is hidden by default.
4.Validates proper functioning of the hamburger menu toggle.
5.Tests that there is at least one entry in feed.
6.Tests that new content is loaded by loadFeed().

Resources

https://matthewcranford.com/feed-reader-walkthrough-part-1-starter-code/
Jasmine Documentation. (n.d.). Retrieved from https://jasmine.github.io/
