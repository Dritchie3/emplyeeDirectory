# Employee Directory
Homework assignment where the goal is make an employee directory using React.js, populating it with random employees from an api, and allowing the user to search/sort the results.

## Deployed App:

## Github: https://github.com/Dritchie3/emplyeeDirectory

## Portfolio Page: https://dritchie3.github.io/AboutMe/portfolio.html



## Description 
Primary goal of app was to use React for the first time. The app takes in a set of random employees from the API Random User Generator (randomuser.me). It stores the random employees in context. The employees are mapped over and displayed in a table format. The user is able to sort the employees by first name or age by clicking on the column name. The user is also able to search by the users first name with the search input.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).




## Installation
#### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

## Usage 
This was primarily made to meet the requirements of a homework assignment. It could be used as the basis for a to-do app.

## Credits 
I created this code based on the homework prompt created by Triology Education Services. Certain pieces of code I used online resources for help. I have included citations in the form of comments throughout the code. Image credits are located below the image.

## Contributing 
I was the only one to work on this project, but of course I had help from my instructor, TA's, and classmates.

## Challenges
The major challenge was using React for the first time. Figuring out how to properly implement the hook useEffect was a struggle for me for awhile. I built out my components before thinking about how I would pass values around through components, which resulted in me having to learn how to implement the handle useContext. This allowed me to pass around the employees and update them without having to worry about parent child relationships to allow for prop passing.


# Unit 19 React Homework: Employee Directory

## Overview

For this assignment, you'll create a employee directory with React. This assignment will require you to break up your application's UI into components, manage component state, and respond to user events.

## User Story

* As a user, I want to be able to view my entire employee directory at once so that I have quick access to their information.

## Business Context

An employee or manager would benefit greatly from being able to view non-sensitive data about other employees. It would be particularly helpful to be able to filter employees by name.

## Acceptance Criteria

Given a table of random users, when the user loads the page, a table of employees should render. 

The user should be able to:

  * Sort the table by at least one category

  * Filter the users by at least one property.

## Commit Early and Often

One of the most important skills to master as a web developer is version control. Building the habit of committing via Git is important for two reasons:

1. Your commit history is a signal to employers that you are actively working on projects and learning new skills

2. Your commit history allows you to revert your code base in the event that you need to return to a previous state

Follow these guidelines for committing:

* Make single purpose commits for related changes to ensure a clean, manageable history. If you are fixing two issues, make two commits

* Write descriptive, meaningful commit messages so that you and anyone else looking at your repository can easily understand its history

* Don't commit half done work, for the sake of your collaborators (and your future self!)

* Test your application before you commit to ensure functionality at every step in the development process

We would like you to have well over 200 commits by graduation, so commit early and often!


## Submission on BCS

You are required to submit the following:

* the URL to the deployed application

* the URL to the Github repository

