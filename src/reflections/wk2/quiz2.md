# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
You can use let, var, and const. Var is outdated and global, while const and let are local.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a block of code that is put under one tag. So whenever the tag is called, the whole block is call.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The first one is Single Responsibility. It means that a class should only do one thing. The second one is Open for Extension, closed for modification. This means you should be able to easily add stuff, but not easily change pre-existing stuff. The third one is Liskov Subsitution. That means that a class and a subclass should be decently interchangable. The fourth one is Interface Segregation. This one is that interfaces should be broken up into smaller pieces so that they can be more accurately defined and coded. The last one is Dependency Inversion.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
banana's position is 1. I know this since it starts at 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
You would do them.push(you). This should push them into you, which sounds weird.
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(x=3){
  x++
}else(x=3)
This function checks if x is = to three. If it is, it increases x by one. If x is not, it sets x equal to 3. 
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
That is the final expression. You would put i++.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The DOM is the Document Object Model. The DOM first accesses the HTML file
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
They are Boolean, Null, Undefined, String, Number, Object, Symbol, BigInt, and Properties. I couldn't find a direct answer, but I pieced together what I found.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
The parameter is the variable you put in. The arguement is what gets put into the code and run.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive value stores the actual value, while a reference value stores where the value is located.
```