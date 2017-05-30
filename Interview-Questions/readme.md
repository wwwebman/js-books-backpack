# Front-End Interview Questions
## Content

1. [General Questions](#general-interview-questions)
1. [Javascript](#javascript-interview-questions)
1. [Javascript Coding](#javascript-coding-questions)
1. [HTML](#html-interview-questions)
1. [CSS](#css-interview-questions)


### General Interview Questions
* What is REST?
[Answer](http://searchmicroservices.techtarget.com/definition/REST-representational-state-transfer)
* What is the difference between PUT and PATCH methods in REST?


### Javascript Interview Questions
## 1. HTML
1. What the main things you can do to increase page speed loading?
## 2. CSS
1. What different between mobile first and mobile last?


### Javascript Interview Questions

* What is the JavaScript Event Loop? - [Answer](http://altitudelabs.com/blog/what-is-the-javascript-event-loop/); [Video Answer](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=1244s)

* What is the Event Delegation? - [Answer](https://davidwalsh.name/event-delegate)


### Javascript Coding Questions

* Write a `pipefy` function where a string received is returned, but with the `|` character between each character. Make it possible to execute function in this way:
```javascript
'javascript'.pipefy()
```

Answer:
```javascript
String.prototype.pipefy = function() {
	return this.split('').join('|');
}
```
