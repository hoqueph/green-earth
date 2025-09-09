# Question 1 : What is the difference between var, let, and const?

Ans: 
var: Function-scoped. If declared outside any function, it becomes a global variable. It can be reassigned and redeclared. Not block-scoped.

let: Block-scoped. It can be reassigned but cannot be redeclared in the same scope.

const: Block-scoped. It must be initialized when declared, cannot be reassigned, and cannot be redeclared. However, the contents of objects or arrays declared with const can still be changed.

# Question 2 : What is the difference between map(), forEach(), and filter()?

Ans:
map() : It is used to create a new array by applying a transformation function to every element in the original array. The new array will always have the same length as the original. We use map() when we want to transform an array of data into a new array — for example, converting an array of objects into an array of specific properties, or formatting data.

forEach() : It is used to execute a function for each element in the array. It’s used for its side effects, not for transforming data or creating a new value. It's typically used when we want to perform an action on each item — such as logging values, updating the UI, or making an API call for each element.

filter() : It is used to create a new array containing only the elements that pass a test provided by a callback function. It’s useful for filtering out unwanted items. For example, we might use it to get all users who are admins or find all products above a certain price.

# Question 3 : What are arrow functions in ES6?

Ans: Arrow functions are a powerful tool for writing cleaner and more predictable code, especially when dealing with callbacks and preserving the this context. They are often used for short callback functions such as in map, filter, reduce, forEach, and setTimeout.

# Question 4 : How does destructuring assignment work in ES6?

Ans: Destructuring assignment in ES6 provides a powerful and convenient way to extract values from arrays and objects, making code more readable and maintainable. Common use cases include array destructuring and object destructuring.

# Question 5 : Explain template literals in ES6. How are they different from string concatenation?

Ans: Template literals are a new way to create strings in JavaScript, using backticks (`) instead of single or double quotes. So we can write html codes without worrying about single or double quote. Also using variables inside strings were never been easier. They make creating dynamic strings much cleaner and more readable compared to the old way of concatenation.