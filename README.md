# MovieFone-Solo-Project
# IMDB Automation Testing Solo Project

- [Summary](#summary)
- [Setup](#setup)
- [Running Tests](#running-tests)
- [What Do We Test](#what-do-we-test)
- [How Do We Test](#how-do-we-test)
  - [Page Objects](#page-objects)
  - [Data Files](#data-files)

## Summary

This project is meant to demonstrate my proficiency in automation doing various searches on MovieFone.com 
I'm using Jest as the  test platform, and Selenium Webdriver to achieve the website connection.

## Setup

This is how to set up the project.
1. clone it!
1. `npm i`

## Running Tests

To run all the tests, use the command: `npm test`
To run a specific test, use the command: `npx jest test_name`

## What Do We Test

The functionality to be tested: 

 1.   Search for Movies Theaters by Zip Code.
 2.   Change the location bu updating the Zip Code.
 3.   Search for a specific Movie Title in the Search Bar on the Home Screen.
 4.   Browse a list of all the New Movies.
 5.   Browse a list of all movies the are Coming Soon.
 6.   Search for all new DVD releases.
 7.   View the Latest movie trailers.
 8.   View the Latest Movie News.
 9.   View what is currently available on streaming Platforms.
 10. Search for movies by genre ( i selected horror for this search).


## How Do We Test

I organized the tests using this structure:
- Tests
- - data
- - - zipcode.json
- - - movies.json
- - pageObjects
- - - BasePage.ts
- - searchTests.test.ts
- - browseTests.tests.ts
- - viewTests.tests.ts

### Page Objects

I made page objects for these pages to represent: a BASE PAGE that I use for working with base page elements ONLY and COMMON methods that can be used on ANY page, and other pages which I use for working with specific pages and methods that can be used ONLY on these pages.

### Data Files

Iteration is key to test some specific functionality, so I created data files for search by movie title and person's name.

## Author
- Wesley hampton
