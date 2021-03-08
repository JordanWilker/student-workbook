# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
They stand for create, read, update, and delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
There is post for create, get for read, put is update, and delete for delete.
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM is object relational mapping. It is a way of organizing and connecting information to each other for your api server. 
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
The Post and Put request contain a body, because you are changing or adding info. The other two just see or delete info.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
The first blank is an await coding model, while the other is an async coding model. 
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
All three parts of the missing code is mongoose.
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is a function that has access to both the request and the response. You can use this to edit the request if before you get the response, and can help with security.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
The request pipeline delivers info, while the response pipeline returns it.
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
res.send(await tagService.create(winter))
```