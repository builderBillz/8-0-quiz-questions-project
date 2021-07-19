**Q:** Show an example of declaring a function, then name the parts of a function and describe what they do?

> A

```js
function addNumbers(num1, num2) {
    return(num1 + num2)
}
```

In this example function is declaring a function. addNumbers is the name of the function that has been declared. (num1, num2) These will be used to define our function and are known as parameters. Within the curly braces { return(num1 + num2) } is our function body which define our function or tell js what our function does. The opening curly brace is known as the start of the function and the closing curly brace signals that we are at the end of the respective function

**Q:**

Now call the function that you created and explain the difference between this and declaring a function.

> A

```js
addNumbers(num1, num2) 
```

When a function is declared it is being created with intent to use within a js or it is given meaning rather. Here we are calling the function so the js looks for the function declaration of addNumbers and uses those instructions to act upon the arguments(num1, num2), which were our parameters in declaring our function.

**Q:**

```js

function sizeCompare(num1,num2) {
    if (num1 > num2) {
        return `${num1} is greater than ${num2}`
    } else if(num1 < num2) {
        return `${num1} is less than ${num2}`
    } else {
        return `${num1} is equal ${num2}`
    }
}


console.log(sizeCompare(5,7))
```
What will log to the console and why?

> A

5 is less than 7


Within our function we have an if statement which requires certain conditions to be met to store different values. Our arguments are given the value 5 as num1 and 7 as num2 based on the order they were written when we called our function. The condition that was met is (num1 < num2) because 5 is less than seven so `${num1} is less than ${num2}` is logged to the console replacing num1 with 5 and num2 with 7







