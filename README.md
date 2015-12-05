# Feed Reader Project using Jasmine

Jasmine framework shows us the benefits related to testing, and this project uses some of the methods that this frameworks provides us.

## About

All tests are in jasmine/spec/feedreader.js and are about:

1. Make sure that the allFeeds variable has been defined and that it is not empty.
2. It ensures that all objects (inside allFeeds variable) have a URL defined and the URL is not empty.
3. It ensures that all objects (inside allFeeds variable) have a name defined and the name is not empty.
4. It ensures the menu element is hidden by default.
5. It ensures the menu changes visibility when the menu icon is clicked.
6. It ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
7. It ensures when a new feed is loaded by the loadFeed function that the content actually changes.

## How to run

1. Download or clone the project.
2. Open index.html in your favourite browser and see the results.
3. If you want to add more tests, include them in jasmine/spec/feedreader.js
