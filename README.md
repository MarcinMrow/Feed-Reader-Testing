# Front-End Nanodegree Feed Reader Testing Project

1. Project Overview

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

This project:
- is a web-based application that reads RSS feeds,
- includes [Jasmine](http://jasmine.github.io/). 

Jasmine is used to write a number of tests against a pre-existing application which test the underlying business logic of the application as well as the event handling and DOM manipulation.

Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript.

Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.

2. Created for [**Front-End Web Developer Nanodegree Program**](https://eu.udacity.com/)

## How to run the project

1. Download/ clone the repository: 
```
$ git clone https://github.com/MarcinMrow/Feed-Reader-Testing.git
```
2. Open **index.html** in the browser.

## Project completion: check list.

Review the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric).

1. Take the JavaScript Testing [course](https://www.udacity.com/course/ud549)
2. Download the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
3. Review the functionality of the application within your browser.
4. Explore the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) to gain an understanding of how it works.
5. Explore the Jasmine spec file in **./jasmine/spec/feedreader.js** and review the [Jasmine documentation](http://jasmine.github.io).
6. Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
7. Return the `allFeeds` variable to a passing state.
8. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
9. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
10. Write a new test suite named `"The menu"`.
11. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
12. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
13. Write a test suite named `"Initial Entries"`.
14. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
15. Write a test suite named `"New Feed Selection"`.
16. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
17. No test should be dependent on the results of another.
18. Callbacks should be used to ensure that feeds are loaded before they are tested.
19. Implement error handling for undefined variables and out-of-bound array access.
20. When complete - all of your tests should pass. 
21. Write a README file detailing all steps required to successfully run the application. If you have added additional tests (for Udacious Test Coverage), provide documentation for what these future features are and what the tests are checking for.

## Dependencies

1. Feed Reader has been created as the Udacity Project and based on the **starters code**.
2. **Jasmine**: [A JavaScript Testing Framework](https://jasmine.github.io/tutorials/your_first_suite).
3. **Jasmine**: [introducton.js](https://jasmine.github.io/2.0/introduction.html).
4. **GIT**: [Writing on GitHub](https://help.github.com/articles/basic-writing-and-formatting-syntax/#links).
5. **Style Guidelines**: [Udacity Frontend Nanodegree Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/index.html).
6. **Udacity Community**: [Forums](https://discussions.udacity.com/) and [Knowledge](https://knowledge.udacity.com/) and [Slack](https://slack.com/).
7. **Java Script Testing**: [course](https://eu.udacity.com/course/javascript-testing--ud549).

## Instructions

Students should use this [rubric](https://review.udacity.com/#!/rubrics/18/view) for self-checking their submission.