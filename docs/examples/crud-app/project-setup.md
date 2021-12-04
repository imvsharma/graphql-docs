# Project Setup

We are building this simple app by using of **GraphQL** with **Express JS (Minimalist NodeJS Framework)**

##  Prerequisites

* Basic knowledge of **Javascript with ES6**
* Basic knowledge of **NodeJS**
* You should have installed latest version of NodeJS
* Some basic knowledge of **GraphQL** like **Query** and **Mutation**


##  Creating a Simple NodeJS Project

Running the below command for creating the nodejs project.

```
npm init -y
```

##  Installing Dependencies

Installing the required dependencies by running below command.

```
npm install express express-graphql graphql --save
```

##  Creating a Simple ExpressJS Server

Creating a simplest express server by running below code.

```
var express = require('express');
var app = express();
app.listen(4000);
console.log('Running a Express server at http://localhost:4000');
```