# Feed reader testing

## Getting Started
### Prerequisites
For run the tests, you only need a compatible browser.
### Installing
Installation is not necessary. You only need to click in the `index.html` file and click on the different tests that appears at the bottom of the page.
### Required Test
* Tests to make sure that the `allFeeds` variable has been defined and that it is not empty.
* Test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
* Test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
* Test that ensures the menu element is hidden by default.
* Test that ensures the menu changes visibility when the menu icon is clicked.
* Test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

## Build with
* [Atom](https://atom.io/) - A code editor
* [JavaScript](https://www.javascript.com/) - A language for coding
* [Jasmine](https://jasmine.github.io/) -  A behavior-driven development framework for testing JavaScript code.

## Authors
* **Isabel Clemente** - [Isabel Git](https://github.com/isactenofora)

## License
This project is licensed under the MIT License
