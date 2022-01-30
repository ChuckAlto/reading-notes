# 301 Reading Twelve

## Crud

### Rest Methods

- In your own words, describe what each group of status code represents:

100’s = informational status codes, extends information to the client about what the server is doing or what has failed.

200’s = Success codes, informs the client that whatever request was made has been successful with the client.

300’s = Redirection codes, Lets the client know that what they are looking for is no long where they are looking then if the server has the information as to the new location directs them to that new location.
400’s = Client Error Codes, when a client sends a request to the server and the request is invalid or missing or something is wrong with the request. This lets the client know that they need to correct the request.
500’s = Server codes, Lets the client know that the server is where the error is happening, whether it is because the server is not reachable or overwhelmed .

- What is a status code 202?

answer- Accepted, the request was good but has not finished processing

- What is a status code 308?

answer- Permanent Redirect, tells client that current url is no longer valid and the new url must be used in the future.

- What code would you use if an update didn’t return data to a client?

answer- 204 no content.

- What code would you use if a resource used - to exist but no longer does?

answer- 410 gone.

- What is the ‘Forbidden’ status code?

answer- 403 Forbidden.

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?

answer-when we deploy we need to use something that is not our local host. 

- What is middleware?

answer- code that runs when a server gets a request.

- What does app.use(express.json()) do?

answer- lets the middleware json be accepted by the server.

- What does the /:id mean in a route?

answer- it is a parameter.

- What is the difference between PUT and PATCH?

answer- updates only what the user gives and not all the information at once.

- How do you make a default value in a schema?

answer- type in default: Date.now

- What does a 500 error status code mean?

answer- generic error response from the server.

- What is the difference between a status 200 and a status 201?

answer- 200 a request has been received and is bing processed, a 201 request was successful and a resource has been created.

[main](README.md)
