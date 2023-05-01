# Basic Javascript Project

JavaScript is a high-level, interpreted programming language that is used to create dynamic and interactive web pages. It was first developed by Netscape in 1995 and has since become one of the most popular programming languages in the world. JavaScript is often used in conjunction with HTML and CSS to add functionality to web pages and create user interfaces that respond to user actions. It can also be used on the server-side (using Node.js) to build web applications and back-end systems. JavaScript is supported by all major web browsers and can also be used in other environments, such as desktop and mobile applications.

That's why here I uploaded two basic projects focused mainly on JavaScript along with HTML and little bit of BootStrap :

## Real-time Clock using JavaScript
<hr>
<img src="https://github.com/thakurboy004/Basic-JavaScript-Projrects/blob/main/Screenshot%20from%202023-04-30%2021-26-47.png">
<hr>

### Main functions used in this Project:
`setInterval()` : The setInterval() function is a built-in function in JavaScript that allows you to repeatedly execute a piece of code at a specified time interval. The setInterval() function takes two parameters: the first parameter is the function you want to execute, and the second parameter is the time interval in milliseconds.

For example, the following code will execute the myFunction() function every 1000 milliseconds (1 second):

```javascript
setInterval(myFunction, 1000);
```
When the setInterval() function is called, it returns an ID that you can use to stop the interval at any time using the clearInterval() function. For example, the following code will stop the interval with the ID myInterval:

```javascript
clearInterval(myInterval);
```
The setInterval() function is commonly used for tasks that require periodic updates or animations, such as updating the time on a clock, refreshing a chat window, or scrolling a ticker. However, it is important to use setInterval() judiciously, as excessive use can lead to poor performance and increased battery consumption on mobile devices.

## TODOs list using JavaScript
<hr>
<img src="https://github.com/thakurboy004/Basic-JavaScript-Projrects/blob/main/Screenshot%20from%202023-04-30%2021-50-27.png">
<hr>

### Main functions used in this project:

`getElementById()`: This function allows you to select an element on the page by its ID attribute. For example:
```javascript
document.getElementById("myElement");
```
`addEventListener()`:The addEventListener() function takes two parameters: the type of event to listen for (such as "click" or "mouseover") and the function that should be executed when the event occurs. For example:
```javascript
var myButton = document.getElementById("myButton");

myButton.addEventListener("click", function() {
  // do something when the button is clicked
});
```
In this example, the event listener is added to a button element with an ID of "myButton". When the button is clicked, the anonymous function passed as the second parameter to addEventListener() is executed.

`localStorage`:Local storage is implemented using the localStorage object, which is part of the Web Storage API. The localStorage object has methods for setting, getting, and removing data from the local storage. Here are some examples:

1. Setting a value in local storage:
```javascript
localStorage.setItem("myKey", "myValue");
```
In this example, the setItem() method is used to store a value of "myValue" with the key "myKey" in local storage.

2. Getting a value from local storage:
```javascript
var myValue = localStorage.getItem("myKey");
```
In this example, the getItem() method is used to retrieve the value of "myKey" from local storage and store it in the variable myValue.

3. Removing a value from local storage:
```javascript
localStorage.removeItem("myKey");
```
In this example, the removeItem() method is used to remove the value of "myKey" from local storage.

`JSON`:In JavaScript, JSON data is represented as a JavaScript object, and can be created and manipulated using built-in functions such as JSON.parse() and JSON.stringify().

1. `JSON.parse()`:  This function is used to parse a JSON string and convert it into a JavaScript object. For example:
```javascript
var jsonString = '{"name": "John", "age": 30}';
var myObject = JSON.parse(jsonString);
```

In this example, the JSON.parse() function is used to convert the jsonString variable into a JavaScript object, which is then stored in the myObject variable.

2. `JSON.stringify()`:  This function is used to convert a JavaScript object into a JSON string. For example:
```javascript
var myObject = { name: "John", age: 30 };
var jsonString = JSON.stringify(myObject);
```

In this example, the JSON.stringify() function is used to convert the myObject variable into a JSON string, which is then stored in the jsonString variable.
