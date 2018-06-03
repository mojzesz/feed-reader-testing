# Feed Reader Testing ↘︎

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development".

## How To Run The Application

⚀ Open `index.html` in your browser.

## What I Did

- [x] Wrote a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
- [x] Wrote a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
- [x] Wrote a new test suite named "The menu".
- [x] Wrote a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
- [x] Wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
- [x] Wrote a test suite named "Initial Entries".
- [x] Wrote a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
- [x] Wrote a test suite named "New Feed Selection".
- [x] Wrote a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
- [x] Implemented error handling for undefined variables and out-of-bound array access.

