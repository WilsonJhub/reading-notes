# Spring Boot and OAuth2
-- - 

Samples are all single-page apps using Spring Boot and Spring Security on the back end.  
- There are a few samples that are built off of each other while adding new features at each step:  
  - _**simple**_: a very basic static app with just a home page and unconditional login via Spring Boot’s OAuth 2.0 configuration properties (if you visit the home page, you will be automatically redirected to GitHub).

  - **_click_**: adds an explicit link that the user has to click to login.  

  - **_logout:_** adds a logout link as well for authenticated users.  

  - **_two-providers:_** adds a second login provider so the user can choose on the home page which one to use.  

  - **_custom-error:_** adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.  

-- - 
Source:  
- [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)