# Working with Relationships in Spring Data REST  
-- - 

Libraries and Addresses have a one-to-one relationship by using the @OneToOne annotation. 

## Creating the Resources  
- First, add a library by typing - "Content-Type:application/json" 
- then the API will return the JSON object. 
- The result of the POST request is a JSON object containing the Address record  


### Creating the Associations  

After persisting both instances, we can establish the relationship by using one of the association resources.

This is done using the HTTP method PUT, which supports a media type of text/uri-list, and a body containing the URI of the resource to bind to the association.

Source:  
- [Working with Relationships in Spring Data REST](https://www.baeldung.com/spring-data-rest-relationships)