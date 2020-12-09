# Introduction-to-Requests-with-ES6

In the previous lesson, we spent a lot of time dealing with asynchronous data (remember AJAX/ Asynchronous JavaScript And XML?). Many of our web page interactions rely on asynchronous events, so managing these events is essential to good web development.

To make asynchronous event handling easier, promises were introduced in JavaScript in ES6:

Mozilla Development Network: Promises
A promise is an object that handles asynchronous data. A promise has three states:

pending : when a promise is created or waiting for data.
fulfilled : the asynchronous operation was handled successfully.
rejected : the asynchronous operation was unsuccessful.
The great thing about promises is that once a promise is fulfilled or rejected, you can chain an additional method to the original promise.

In this lesson, we will explain how to use fetch(), which uses promises to handle requests. Then, we will simplify requests using async and await.

We’ll use the Datamuse API for GET requests and Rebrandly URL Shortener API for POST requests. For you to complete the lessons on POST, make sure you create a Rebrandly API Key by following the instructions in the article below:
