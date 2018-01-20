# January 2018 - Fullstack Challenge

## Clone a Twitter / Snapchat Hybrid

Twitter allows for real time messaging "with the world", following users, tagging posts, targetting posts @ certain users, etc.

Snapchat has one feature that Twitter lacks - what you post to Snapchat is temporary, it does not persist "forever".

This challenge is to clone Twitter, but using Snapchat's message retention strategy.

## Features to implement

As a user, I can:

* Login via OAuth
* Post a message that is X characters long
* View a stream of the messages that have been posted
* View trending #TAGS
* Include a #TAG in my post
* @MENTION a user in my post
* Follow other users
* View a stream of messages from only those I follow
* View a stream of messages that match a particular tag
* Be notified when I am mentioned in a post
* Expect that my messages will disappear after X hours

As a non-authenticated user, I can:
* View the landing page
* View a stream of the messages that have been posted
* View trending #TAGS
* View a stream of messages that match a particular tag

_(What to set X to is your decision to make for your application.)_

## Tasks to complete

Total Points Earned:

* [ ]  (20 Points) Implement pre-login landing page
* [ ]  (20 Points) Implement login
* [ ]  (20 Points) Implement frontend with input for entering post
* [ ]  (20 Points) Implement backend for receiving post
* [ ]  (30 Points) Implement backend for saving post
* [ ]  (50 Points) Implement mechanism for backend to send post to all connected clients (suggestion: use web sockets)
* [ ]  (20 Points) Implement frontend for showing stream of posts
* [ ]  (50 Points) Implement functionality that deletes messages from the backend after X time
* [ ]  (50 Points) Implement functionality that instructs clients to fade out deleted messages
* [ ]  (20 Points) Implement functionality for recognizing #TAGS in posts
* [ ]  (20 Points) Implement a "trending" sidebar which shows which #TAGS are currently being most used
* [ ]  (20 Points) Implement functionality for recognizing @MENTIONS in posts
* [ ]  (20 Points) Implement notifications screen where a user can see a log of messages in which they were @MENTIONED
* [ ]  (20 Points) Implement "follow" functionality and a separate post stream where a user can see only the messages of those they follow

### Bonus points earned

* [ ]  
* [ ]  
* [ ]  

## Bonus point opportunities

* 5 points per test case written and passing
* 50 points for following a git workflow (a branch for each feature, a commit for each change)
* 50 points for using a CSS Preprocessor (Sass/Less/Stylus/etc)
* 50 points for using a frontend framework/library (Angular/Vue/React/etc)
* 50 points for configuring linting on the project and automating lint before deploy
* 50 points for setting up continuous integration which automatically tests, lints, builds, and deploys on git commit
* 50 points for optimizing the production build (above 95 on google pagespeed insights, both mobile and desktop)

## Rules

* use whatever technologies / languages you want
* team up if you want, claim an extra 100 points for each team member if you complete the entire project together
* no deadline, but bragging rights if you finish quick (and to a good standard)
* 'done' project will have code and live app available online
