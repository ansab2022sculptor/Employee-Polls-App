# Employee Polls Web App

## Description:

This Project is about Employee Polls App that is built in react redux. In this app, every employee of the company can access the application and create a poll with two options. Employees can then vote on these options and see which one have the most votes. The process goes like this: An employee is asked a question in the form: “Would you rather [option A] or [option B] ?”. Also, Answering "neither" or "both" is not possible in this poll.

The person using this application will have a way of impersonating/logging in as an existing user. (This would be as simple as having a dropdown that appears at the root of the application that lets the user select a user from the list of existing users.

Once the user logs in, the user will be able to toggle between his/her answered and unanswered polls on the home page, which is located at the root. The polls in both categories are arranged from the most recently created (top) to the least recently created (bottom). The unanswered polls should be shown by default, and the name of the logged in user should be visible on the page.

The application will show a 404 page if the user is trying to access a poll that does not exist.

## How to run this project

To run this project, write 2 commands in project terminal

- `npm install` will install all project dependencies
- `npm start` will run this project in localhost:3000
