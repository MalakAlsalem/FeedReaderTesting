Feed Reader Testing Project
============================

This is a project for Front-End Web Development Nanodegree from [Udacity][1].
wrote a number of tests against a pre-existing application with Jasmine, to test the underlying business logic of the application as well as the event handling and DOM manipulation.

**To run the application:**
Download the repository, extract it and open index.html in your browser to see the working tests.

**Tests implemented**
-  Test ensures *allFeeds object* has a URL defined and that the URL is not empty.
-  Test ensures *allFeeds object* has a Name defined and that the URL is not empty.
-  Test ensures *the menu* element is hidden by default.
-  Test ensures *the menu* changes visibility when the menu icon is clicked. This test have two expectations: does the menu display when clicked and does it hide when clicked again.
-  Test that ensures when the *loadFeed function* is called and completes its work, there is at least a single .entry element within the .feed container.
-  Test ensures when a new feed is loaded by *the loadFeed function* that the content actually changes.

[1]: https://www.udacity.com/
