# Calculator Cypress Challenge

## Overview

The goal of this challenge is to create a simple cypress test suite for a simple web app. The simple web app that you will be testing consists of:

  - A React frontend calculator that takes a simple input and returns the appropriate result
  - A Node.js backend using express that consists of a single route and executes the following function:

## Settings

The project already has cypress setup so you can worry only about writing the tests :smile:. Create yout tests inside `cypress/e2e` and run `npm run cy:open` to view your tests.

### Test Cases

  - Should be able to make calculations;
  - Should display username when authenticated;
  - Should login an existing user;
  - Should register a new user;
  - Should show an error message if there's an error registering;

## Goal

Create cypress tests that test for the above cases. Bonus points for going above and beyond.

## Running the Example application

### Clone repository
Run `git clone https://github.com/igorcap/calculator-testing`

### Install Dependencies
Run `npm install` from the top level folder of this repository

### Running The App
Run `npm run start` in the main folder in your command line to start the server and go to http://localhost:8001 in your browser to view the app.

### Running the Tests

Run `npm run cy:open` or `npm run cy:run`.

## Submitting
Fork this repository, commit your code into that fork, and let us know when you are ready for us to review it! Best of luck!