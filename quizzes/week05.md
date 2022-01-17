# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
Create Read Update Delete
or 
GET
POST
PUT
DELETE
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
GET
POST
PUT
DELETE
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM stands for object relational mapping. When using MongoDb we use the Node ORM
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
The two HTTP requests that include a body is the .Put and the .Delete method
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
Synchronous       &        Asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
a) mongoose & b) "mongoose"
c) mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware or more particular a middleware function acts as a gatekeeper in sense. It has access to a request object and a response objects. In our case use, we've used to to authorize a user to carry out certian actions in the application. Therefore it executes code when a parameter passes a check which makes changes to the request and response objects / ends a requests / calls to the next action in the code.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
a)Request  b)Response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
?tag=winter
```