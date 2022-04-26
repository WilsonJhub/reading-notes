# CRUD  

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents: 
  - 100's = Informational status codes that inform the client that the header portion of the request has been received but not processed.  
  - 200's = The request from the client was accepted.  
  - 300's = The resource that is requested, is not available.   
  - 400's = Client errors. Causes: timeouts, wrong URI, missing authentication, etc.
  - 500's = Server errors. Indicates a problem with an overwhelmed server.  


2. What is status code '202'?  
  - 202 Accepted response status code indicates that the request has been accepted for processing,  
    but the processing has not been completed; in fact, processing may not have started yet.
3. What is a status code 308?  
  - The resource requested has been definitively moved to the URL given by the Location headers.
4. What code would you use if an update didn’t return data to a client?  
  - 404
5. What code would you use if a resource used to exist but no longer does? 
  - 404
6. What is the ‘Forbidden’ status code?
  - 403


1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?  
  - So that your .env file has a reference to pull data from?
2. What is middleware?  
  - database middleware, application server middleware, message-oriented middleware,  
    web middleware, and transaction-processing monitors.
3. What does app.use(express.json()) do?  
  - It parses incoming JSON requests and puts the parsed data in request. body
4. What does the /:id mean in a route?  
  - it is an id for the parent file?
5. What is the difference between PUT and PATCH?  
  - PUT is a method of modifying resource where the client sends data that updates the entire resource.  
    PATCH is a method of modifying resources where the client sends partial data that is to be  
    updated without modifying the entire data.
6. How do you make a default value in a schema?  
  - const schema = new Schema({  
      name: String,  
      description: { type: String, default: '' }  
});  
7. What does a 500 error status code mean?  
  - Internal Server Error  
8. What is the difference between a status 200 and a status 201?  
  - 201 was received and understood and is being processed.  
  - 201 status code indicates that a request was successful and as a result, a resource has been created
