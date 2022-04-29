# Authentication  
  
## What is OAuth  

  1. What is OAuth?  
    - OAuth is an open-standard authorization protocol or framework that describes how unrelated   
    servers and services can safely allow authenticated access to their assets without   
    actually sharing the initial, related, single logon credential.  
  2. Give an example of what using OAuth would look like.  
    - example of OAuth is when you go to log onto a website and it offers  
    one or more opportunities to log on using another website’s/service’s logon.  
  3. How does OAuth work? What are the steps that it takes to authenticate the user?   
    - First website connects to the second website on behalf of the user.  
    - The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.  
  4. What is OpenId?
    - "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."  



## Authorization and Authentication flows  

1. What is the difference between authorization and authentication?  
  - authentication is the process of verifying who someone is, whereas authorization is the process of verifying what specific applications, files, and data a user has access to.  
2. What is Authorization Code Flow?  
  - used to obtain both access tokens and refresh tokens and is optimized for confidential clients.  
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?  
  - is the recommended form of authenticating RingCentral users and exchanging tokens in client-side applications
4. What is Implicit Flow with Form Post?
  - The web app requests and obtains tokens through the front channel, 
   without the need for secrets or extra backend calls.
5. What is Client Credentials Flow?  
  - permissions are granted directly to the application itself by an administrator.  
6. What is Device Authorization Flow?
  - The OAuth 2.0 Device Authorization Grant (aka Device Flow) is an extension to the original OAuth 2.0 spec.  
  It solves the problem of obtaining access tokens on devices where the user has limited possibilities to enter its credentials.
7. What is Resource Owner Password Flow?   
  - allows exchanging the username and password of a user for an access token and, optionally, a refresh token.