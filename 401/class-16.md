# Reading Notes
-- -
## Spring Security Architecture
-- -
### Authentication and Access Control

The main strategy interface for authentication is AuthenticationManager, which has only one method:  
- public interface AuthenticationManager {  

  Authentication authenticate(Authentication authentication)  
  throws AuthenticationException;  
  }

An AuthenticationManager can do one of 3 things in its authenticate() method:  

- Return an Authentication (normally with authenticated=true) if it can verify that the input represents a valid principal.  

- Throw an AuthenticationException if it believes that the input represents an invalid principal.

- Return null if it cannot decide.  

-- -

Source:  
- [Spring Security Architecture](https://spring.io/guides/topicals/spring-security-architecture/)