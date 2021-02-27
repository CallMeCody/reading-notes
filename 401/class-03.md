
### CLASS 03


## REVIEW, RESEARCH AND DISCUSS

#### Middleware Uses

- Managing Data
- Error handling
- Authentication


#### Is route handler a middleware?

- false no its not

#### In what ways can a middleware function end the process and send data to the browser?

- middleware functions end the process by ``` next() ``` and uses ``` response ```
  to send data to the browser.

 #### At what point in the request lifecycle can you “inject” middleware?

 - Middleware lifecycle starts after the request and before the response.

 ### TERMS

 ``` middleware ```  are functions that execute between request and response.

 ```request object ``` is the data sent from the client to the server.

 ```response object ``` is the data sent from the server to the client.

 ``` application middleware ``` is a software working between request and response.

 ``` routing middleware ```is a routing software working between request and response

 ``` test driven development ``` or TDD is a principle of testing the app 
