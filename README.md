# Project Overview

In this project we were given a web-based application that reads RSS feeds from Udacity Blog, CSS Tricks, HTML5 Rocks & Linear Digressions. I wrote test suite in Jasmine.



# Test Expectation & Task

1. A test suite named `"RSS Feed"`.
  (a) A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
  (b) A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
2. Write a new test suite named `"The menu"`.
  (a) A test that ensures the menu element is hidden by default. 
  (b) A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: check if the       menu is display when clicked and check if it hide when clicked again.
3. A test suite named `"Initial Entries"`.
  (a) A test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
4. A test suite named `"New Feed Selection"`.
  (a) A test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

## What I learnt?

I learnt how to use Jasmine to write a number of tests against a pre-existing application. The test checked the underlying business logic of the application as well as the event handling and DOM manipulation.
