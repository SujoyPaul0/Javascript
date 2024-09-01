json is similar to js objects.
but with less features
json is mor universal

a JavaScript object only makes sense in JavaScript on the other hand Json syntax can be understood by almost every programming language so Json syntax is more un Universal for this reason.

 for this reason we use Json when we send data between  two computers that might use different programming languages.

 json is let's learn about the built in Json object the Json object helps us convert a JavaScript object to Json

 JavaScript has a special feature called Auto boxing. because JavaScript automat automatically wraps the string in an object like a box

 autoboxing does not work with null and undefined.

 ## Dom
 the document object represents/ models the webpage.
 The DOM combines javascript and HTML together and gives javascript the control over the webpage
 when an html element is inside a js then it is converted to an object.
 DOM combines HTML and javascript together.
 Whenever we get a value from the DOM, the value will be a string.
window is a built in object that represents the browser.

### Main Idea of JavaScript
1. Save the data
2. Generate the HTML
3. Make it interactive

in javascript functions are values and we can save it in other variables

setTimeout takes two parameters a fun and a time in ms 1000ms = 1s setTimeout calls the function after the time given. However it doesn't wait for that much time it sets a timer and goes to the next line. This is called Asynchronous code.

Synchronous code will wait for one line to finish before going to the next line.

Arrow Functions 
const arrowFunction = () => {
        console.log('Hello');
      };
      arrowFunction();

when passing a function into another function it is recomended to use arrow functions

regular function declaration enables hoisting which means we can call it before declare it.

when using a function inside an object it is recomended to use this method: 
const object2 = {
        method: () => {

        },
        method() {
          
        }
      };

every html element has a method called .addEventListener() which lets us run some code when we interact with the element.
we can remove a eventListener using .removeEventListener()

.addEventListener let us use multiple event listener also remove evenListeners because of this advantages we use .addEventListener instead of onclick

.filter()  --> 
1. creates a new array[]
2. return true,
  => put valuel in array