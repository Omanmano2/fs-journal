# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The four pillars of object oriented programming are as follows:
Abstraction, encapsulation, inheritance, polymorphism.
Abstraction is to hide away the details of something somewhere.
Encapsulation is the process of making something private by removing access to part of the code 
Inheritance allows for one object to grab the properties of another object
Polymorphism is where types in the same inheritance chain can  do different things
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
let property = (staff.name)
```

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the action of limiting  what pieces your code can access. Essentially encapsulation binds code and data, but you as a coder can tell what data gets passed rather than all data.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Solid stands for single responsibility principle. Which means that a function shouldn't do more than one job. "a class should have on and only on reason to change."
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the archetype or schema used to create objects. For example, a class could be 'Lion' and in that lion, there could be instances of that lion such as time who has no hair and big teeth or bob who has a lot of hair and no teeth. So a class is the blueprint, the instance of the class is the specific thing that belongs to that class
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is a listener between the client's inputs and the accessible object in our model. So it lays dormant until someone wakes him up to do is job of data manipulation.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the MVC pattern is to seperate or organize our files of single responsibility to create a workspace that allows for coders to collaborate on a single application in an effective manner.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller in the mvc pattern is like a waiter in a restuarant. It relays between the view(customer) and the model(kitchen). It recieves an input from the user(view) interprets the data and sends it off to the kitchen(model) and back to the view.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service in mvc is where we modify data, and the only place we modify data. It takes the order from the controller and then essentially manipulates the inputs and stores that over to the model.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model in mvc consists of the objects schema or blueprint and loogic specific to that object. Its responsible for handling data from the database and relatys it to the controller.
```
