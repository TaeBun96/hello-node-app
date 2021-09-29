# hello-node-app

## Description
Program runs local Host 3000 , Pull up Text "Hello World" , "Love, Taylor"

## How to create this Program
// Download Visual Studio
// Check to see If Node is installed using  node -v
// After use npm -v
// Open your workspace
// make a file under hello-world call "test.js"
Insert: console.log('hello node');

const express = require('express')
const app = express()

app.get('/', function (req, res) {
res.send('Hello World')
})

app.listen(3000)
// run server using node test.js
// go to localhost:3000 in your browser and it should say " Hello, Node."



