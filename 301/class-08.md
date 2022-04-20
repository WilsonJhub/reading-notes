# Reading  

## API Desgn Best Practices

1. What does REST stand for?  
  -  Representational State Transfer (REST)
2. REST APIs are designed around a ____.  
  - REST APIs are designed around *resources*, which are any kind of   
    object, data, or service that can be accessed by the client.
3. What is an identifier of a resource? Give an example.  
  - A resource has an identifier, which is a URI that uniquely  
    identifies that resource.
      Ex:  
        - https://adventure-works.com/orders/1  
4. What are the most common HTTP verbs?  
  - GET, POST, PUT, PATCH, and DELETE.
5. What should the URIs be based on?  
  - resource URIs should be based on nouns (the resource)  
    and not verbs (the operations on the resource).
6. Give an example of a good URI.  
  - https://adventure-works.com/orders // Good
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  
  - The more requests, the bigger the load. Meaning 'Chatty'
8. What status code does a successful GET request return?  
  - GET retrieves a representation of the resource at the specified URI.  
    The body of the response message contains the details of the requested resource.
9. What status code does an unsuccessful GET request return?  
  - If the server cannot match any of the media type(s) listed,  
    it should return HTTP status code 406 (Not Acceptable).
10. What status code does a successful POST request return?  
  - POST creates a new resource at the specified URI. The body of the request  
    message provides the details of the new resource.
11. What status code does a successful DELETE request return?  
  - Removes the resource at the specified URI.