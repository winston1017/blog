---
layout: post
title:  "Problems encountered"
date:   2017-11-12 10:21:22 -0800
categories: coding
---

Problems encountered when working with the full stack js project:



1. **After setting everything up from a fresh install, I received:**
   Error with modules "methods":

   npm install fresh
   npm install methods

   *error persists*

   ->

   **Solution**:

   rm -rf node_modules
   npm install

   *works!*

   ​

2. **Adding nodemon.js to scripts in package.json threw another error**

   Error: listen EADDRINUSE :::3000

   Meaning port is in-used, reason was because node.js continued to run even after ctrl+c
   ​

   **Solution**: 

   Force close all node.js tasks



MongoDB manual:

https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/