# api-design-nodejs-v3

Learn to Build APIs in Node.js – Model data and REST APIs with Express and MongoDB

## What is an API ?

A server that creates an HTTP interface for interacting with some data - Application programming interface - The name is used EVERYWHERE - Usually a server on some remote machine that dictates how another application can interact with some data - Basic data operations like, CREATE, READ, UPDATE, DESTROY (CRUD)

## What about REST ?

Most popular API design pattern, but is not the silver bullet. Very Blurry - An API design that combines DB resources, route paths, and HTTP verbs to allow applications describe what action they are trying to perform - Popularized when SaaS products starting offering APIs for integrations - Works with basic data modules - Hard to scale with complex data models and client requirements

## Node.js and APIs

Build for high concurrent APIs that are not CPU intensive - Node.js is JavaScript, It's async and event driven. - Single Threaded (can optimize) - When kept async, Node can handle a high amount of concurrent request - Not great for CPU intensive work (Data Crunching, ML, Big maths) - So many open source tools to help build APIs

## Express

The standard API framework for Node.js - Handles all the tedious tasks like managings sockets, route matching, error handling, and more - Open Source - Has a huge community and support from anything that has to do with APIs in Node.js

## MongoDB

The go-to non-relational DB, works like a dream in Node.js

- Non-relational document store that is easy to get started and scales well
- Open source and Backed by a big company
- Tons of hosting solutions
- ORM / ODM and other libs are some of the best for any DB
