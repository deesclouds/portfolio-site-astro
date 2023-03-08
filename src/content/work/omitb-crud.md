---
title: OMITB
publishDate: 2023-02-10 00:00:00
img: /assets/omitb.gif
img_alt: Soft pink and baby blue water ripples together in a subtle texture.
description: |
  Developed a CRUD app inspired by my favorite mystery-comedy on Hulu. 
tags:
  - Design
  - Branding
---
# Only Murders In The Building Crud

A fun **CRUD** app for learning how **CRUD** behaves based on keeping track of a list of quotes from the true crime podcast from the best mystery-comedy show .... **Only Murders in The Building!**

## What is CRUD?

**What is Express?**
A framework for building web applications on top of Node.js

**What is MongoDB?**
Is a database where we store information for our sites and applications.

**What is CRUD?**
Set of operations we get our servers to execute:

Create - (Post) - Make something
Read - (Get) - Get something
Update - (Put) - Change something
Destroy - (Delete) - Remove something

Post, Get, Put, Delete - requests lets us construct REST APIs.

**How does crud works:**
We make requests from our Browser that passes data to our Server, that then passes data to our Database, then our Database responds with data back to our Server, which then our CRUD app lives between our Server and Browser where we can then see that data within out Browser. 

If that doesn't make enough sense right now that's ok. This diagram from zellwk.com can help clarify things: 

<img src="../assets/crud-diagram.png" alt="image of crud">

## Technologies Used:
Html,
CSS - Grid,
JavaScript,
Ejs,
Node.js,
Nodemon,
Express,
MongoDB,
Body Parser - which is deprecated and needs to be updated within the codebase.

## Setup:

Check if Node is installed:

Within your terminal run:

```
node -v
```
If node is not installed download through the [Node](https://nodejs.org/en/) site, or through a package manager: [Homebrew](https://brew.sh/) Mac and [Chocolatey](https://chocolatey.org/) Windows.

## Getting Started:
```
npm init -y
```

The flag -y let's us pass through all the prompts to get started quickly.

### Running Node:
```
touch server.js
```

create our server.js file, then place a console.log with a statement that lets us know that Node is working. 

run ```node server.js``` to display our statement. 

### Running Express:
```
npm install express --save
```

The flag --save has express to save as a dependency within our package.json file. 
Then within 