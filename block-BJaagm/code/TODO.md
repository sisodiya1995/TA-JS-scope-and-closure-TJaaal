1. What does thread of execution means in JavaScript?

Ans - Exection of code step by step by javascript engine are called  thread of exection.

2. Where the JavaScript code gets executed?

Ans- javaScript code executed in GEC. (globle exection context )
 
3. What does context means in Global Execution Context?

Ans- Global Execution Context  executed the javaScript code line by line.

4. When do you create a global execution context.

Ans- when first time javaScript codes run then GEC is created once. 

5. Execution context consists of what all things?

Ans-  1- function exection , 2 -assign value to variable

6. What are the different types of execution context?

Ans- Ans-  1- function exection , 2 -assign value to variable

7. When global and function execution context gets created?

Ans-When the first time javaScript code excuted GEC get created(once) and  FEC gets created many times when function are executed.

8. Function execution gets created during function execution or while declaring a function.

Ans -Function execution gets created during function execution

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)