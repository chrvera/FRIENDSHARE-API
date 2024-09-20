# FRIENDSHARE-API

## Description

This application was developed to create an API for a social network web application where users can share their thoughts, react to friends thoughts and create a friends list. The API stores the data in a NOSQL database using MongoDB.

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Installation

Testing the API requires the user to use the "npm install" command from the terminal. Then the user must start the server by using the "node server.js" command. A walkthrough of testing the API functionality using Insomnia can be found 
here: https://app.screencastify.com/v3/watch/nViPbnAunlr98CoR6AZu

## Contributions

Developers are welcome to submit feedback as well as use for personal use only.

## Questions

For additional questions, reach out to cvera8873@gmail.com