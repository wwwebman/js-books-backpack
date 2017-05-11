# Front-End Interview Questions and Answers
## 1. HTML
1. What the main things you can do to increase page speed loading?
## 2. CSS
1. What different between mobile first and mobile last?
## 3. JS
1. Write a `pipefy` function where a string received is returned, but with the `|` character between each character. Make second function that do the same thing, but in this way > 'some_string'.purify().
```javascript
var pipefy = function(str) {
   return str.split('').join('|');
};
String.prototype.pipefy = function() {
    return this.split('').join('|');
};
```