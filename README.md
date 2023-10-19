# SocialNetworkApi

## Description

​This application is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.
​
This backend can be used for social media startups, and uses a NOSQL database, Express.js for routing, MongoDB database, and Mongoose ODM to handle large amounts of unstructured data, including User and Thought models and schemas and Reaction subdocument schema. When the application is invoked, the server is started and Mongoose models are synced to the MongoDB database.

API GET routes in Insomnia Core for users and thoughts show data and is displayed in a formatted JSON. API POST, PUT, and DELETE routes in Insomnia Core successfully create, update, and delete users and thoughts in the database. API POST and DELETE routes in Insomnia Core successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list.
​

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Packages](#packages)
- [License](#license)
  ​

## Installation

​
Clone the repository, navigate to the project folder on your CLI and run the following command to install Node.js:

`npm install`

## Usage

Run the following command on your CLI to run the application:

`npm start`

​

## Packages

- Express.js https://www.npmjs.com/package/express
- Mongoose ODM https://www.npmjs.com/package/mongoose to connect to MongoDB database

## license

MIT License

Copyright (c) 2023 Godwin Otabor

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
