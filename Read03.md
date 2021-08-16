# Readings: Express REST API

## Review, Research, and Discussion

**1- Name 3 real world use cases where you’d want to change the request with custom middleware**

* *Hight-level payment method security*

* *Track user behavior and stored*

* *Handling error*

**2- True or false: The route handler is middleware?**

* *False*

**3- In what ways can a middleware function end the process and send data to the browser?**

* *when the process is finish , the route handler will send the data*

* *when there is an error in request ,the error handler will send an error*

**4- At what point in the request lifecycle can you “inject” middleware?**

* *after the route and befor the route handler*

**5- What can cause express to error with “Request headers sent twice, cannot start a second response”**

* *when you send more than one request to the server and make interupt between this requests, the server will dell with this requests by send a response have an error.*


