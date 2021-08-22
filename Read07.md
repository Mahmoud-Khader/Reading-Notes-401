# Bearer Authorization

![img](https://developer.atlassian.com/cloud/connect/images/connect-oauth-impersonation-flow.png)

**1- Write the following steps in the correct order**

* *1.Register your application to get a client_id and client_secret*

* *2.Ask the client if they want to sign in via a third party*

* *3.Make a request to a third-party API endpoint*

* *4.Redirect to a third party authentication endpoint*

* *5.Make a request to the access token endpoint*

* *6.Receive access token*

* *7.Receive authorization code*

![img](https://damienbod.files.wordpress.com/2021/04/auth0_apis_04.png?w=1024)

**2- What can you do with an authorization code?**
* *An authorization code allows you to send information, such as a request for an access token, to a secure resource.*

**3- What can you do with an access token?**
* *Access tokens are used to make API requests on behalf of a user*

**3-What’s a benefit of using OAuth instead of your own basic authentication?**
* *OAuth contains authorization requests, access tokens and refresh tokens and widely accepted as the standard for modern web applications. It is well documented and easy to implement.*

# Document the following Vocabulary Terms
## Client ID:
### unique identifier , is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string.

## Client Secret:
### Used to authenticate client and is only known by the server and client

## Authentication Endpoint:
### used to request access tokens or authorization

## Access Token Endpoint:
### used to get an access token or refresh token and its A token endpoint is an HTTP endpoint that micropub clients can use to obtain an access token given an authorization code.

## API Endpoint:
### the connection used to communicate with an API meaning is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service.

## Authorization Code:
### allows you to send information, such as a request for an access token, to a secure resource ,and  is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.

## Access Token:
### used for token-based authentication , are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.

