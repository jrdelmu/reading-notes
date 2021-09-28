# CRUD

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:
  - 100’s = informational status codes
  - 200’s = success codes
  - 300’s = redirection codes
  - 400’s = client error codes
  - 500’s = sever error codes
2. What is a status code 202?
  - 202 is the asynchronous processing of a request
3. What is a status code 308?
  - 308 is a permanent redirect 
4. What code would you use if an update didn’t return data to a client?
  - a code 204
5. What code would you use if a resource used to exist but no longer does?
  - a code 406
6. What is the ‘Forbidden’ status code?
  - code 403

## Build A REST API With Node.js, Express, & MongoDB - Quick 

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
2. What is middleware?
  - software between the client and server
3. What does app.use`(express.json())` do?
  - it will let the server accept json as a body instead of post or get
4. What does the /:id mean in a route?
  - parameter
5. What is the difference beween PUT and PATCH?
  - put creates an object while patch updates it without erasing any previous data
6. How do you make a defalut value in a schema?
  - default: value
7. What does a 500 error status code mean?
  - server error
8. What is the difference between a status 200 and a status 201?
  - a successful post request