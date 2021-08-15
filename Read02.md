# Readings: Express

## Review, Research, and Discussion

**1- What’s the difference between PUT and PATCH?**

*The main difference between the PUT and PATCH method is that the PUT method use the request URI to supply a modified version of the requested resource which replaces the original version of the resource, where's the PATCH method supplies a set of instructions to modify the resource.*

**2- Provide links to 3 services or tools that allow you to “mock” an API for development like json-server**

* [Postman ](https://www.postman.com/)
* [Stoplight ](https://stoplight.io/) 
* [Mocky.io ](https://designer.mocky.io/)

**3- Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?**

*1- Swagger status Codes:*

* 200 : Successful request and response.
* 400 : Bad request
* 404 : Not found
* 500 : Unexpected error

*2- APIDoc.js HTTP status Codes:*

* 200 : Successful request and response.
* 400 : Bad request
* 404 : Not found
* 500 : Unexpected error

**4- Compare and contrast SOAP and ReST**

*1- REST (Representational State Transfer) is truly a “web services” API. REST APIs are based on URIs (Uniform Resource Identifier, of which a URL is a specific type) and the HTTP protocol, and use JSON for a data format, which is super browser-compatible. (It could also theoretically use the SOAP protocol, as we mentioned above.) REST APIs can be simple to build and scale, but they can also be massive and complicated—it’s all in how they’re built, added on to, and what they’re designed to do.*

*2- SOAP (Simple Object Access Protocol) is its own protocol, and is a bit more complex by defining more standards than REST—things like security and how messages are sent. These built-in standards do carry a bit more overhead, but can be a deciding factor for organizations that require more comprehensive features in the way of security, transactions, and ACID (Atomicity, Consistency, Isolation, Durability) compliance. For the sake of this comparison, we should point out that many of the reasons SOAP is a good choice rarely apply to web services scenarios, which make it more ideal for enterprise-type situations.*

![](https://i.stack.imgur.com/DFII3.png)


## Document the following Vocabulary Terms

**1- Web Server**

* *A web server is the technology that serves up a website to users when they visit a URL. On the technical side of things, what that means is that it handles the hypertext transfer protocol (HTTP)*

**2- Express**

* *Web Applications Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.*

**3- Routing**

* *Routing is responsible for matching incoming HTTP requests and dispatching those requests to the app's executable endpoints. Endpoints are the app's units of executable request-handling code. Endpoints are defined in the app and configured when the app starts. The endpoint matching process can extract values from the request's URL and provide those values for request processing. Using endpoint information from the app, routing is also able to generate URLs that map to endpoint*