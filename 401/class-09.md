# Java HTTP Request
-- -

**HttpUrlConnection:**  
- this allows us to perform basic HTTP requests without the use of any additional libraries. All packages needed will be part of the java.net package. 

**Creating Request:**  
- Create a HttpUrlConnection instance using the openConnection() method of the URL clas.  

**Adding Request Parameters:**
- If we want to add parameters to a request, we have to set the doOutput property to true, then write a String of the form param1=value¶m2=value to the OutputStream of the HttpUrlConnection instance:  

**Setting Request Headers:**
- Adding headers to a request can be achieved by using the setRequestProperty() method.  

**Configuring Timeouts:**
- HttpUrlConnection class allows setting the connect and read timeouts.
- To set the timeout values, we can use the setConnectTimeout() and setReadTimeout() methods:  

**Handling Cookies:**  
- The java.net package contains classes that ease working with cookies such as CookieManager and HttpCookie.  
- First, to read the cookies from a response, we can retrieve the value of the Set-Cookie header and parse it to a list of HttpCookie objects.  

**Handling Redirects:**  
- We can enable or disable automatically following redirects for a specific connection by using the setInstanceFollowRedirects() method with true or false parameter.  
- It is also possible to enable or disable automatic redirect for all connections.  

**Reading Response:**
- Reading the response of the request can be done by parsing the InputStream of the HttpUrlConnection instance.  
- To execute the request, we can use the getResponseCode(), connect(), getInputStream() or getOutputStream() methods.

**Reading the Response on Failed Requests**
- If the request fails, trying to read the InputStream of the HttpUrlConnection instance won't work. Instead, we can consume the stream provided by HttpUrlConnection.getErrorStream().  

**Build the Full Response:**
- add the response status information  
- get the headers using getHeaderFields() and add each of them to our StringBuilder in the format HeaderName: HeaderValues.  
- read the response content as we did previously and append it.

-- -
***Source:***  
- https://www.baeldung.com/java-http-request