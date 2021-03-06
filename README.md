
# NoSql Social Network API

  

An API for a social network web application where users can share their thoughts, react to friends thoughts, and create a friend list. This app uses Express, Node, MongoDB and Mongoose to allow users, thoughts, friend lists and thought reactions to be created, updated and deleted with ease in a very user friendly rest api approach.

  

## Walkthrough video

Link to wallkthrough video => https://youtu.be/-7EU4YMjXTc

  

## Screenshot

![enter image description here](https://raw.githubusercontent.com/nadiaalamgir21/social-network-api-nosql/main/assets/s1.PNG)

  
  

## Description

  

```

AS A social media startup

I WANT an API for my social network that uses a NoSQL database

SO THAT my website can handle large amounts of unstructured data

```

  

```

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

  

```

npm install

npm start

make sure mongodb service is running

  

```