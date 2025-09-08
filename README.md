# Question 1 : What is the difference between var, let, and const?

Ans: 
var: Function-scoped. If declared outside any function, it becomes a global variable. It can be reassigned and redeclared. Not block-scoped.

let: Block-scoped. It can be reassigned but cannot be redeclared in the same scope.

const: Block-scoped. It must be initialized when declared, cannot be reassigned, and cannot be redeclared. However, the contents of objects or arrays declared with const can still be changed.

# Question 2 : What is the difference between map(), forEach(), and filter()?

Ans:
map() : map() is used to create a new array by applying a transformation function to every element in the original array. The new array will always have the same length as the original. We use map() when we want to transform an array of data into a new array — for example, converting an array of objects into an array of specific properties, or formatting data.

forEach() : forEach() is used to execute a function for each element in the array. It’s used for its side effects, not for transforming data or creating a new value. It's typically used when we want to perform an action on each item — such as logging values, updating the UI, or making an API call for each element.

filter() : filter() is used to create a new array containing only the elements that pass a test provided by a callback function. It’s useful for filtering out unwanted items. For example, we might use it to get all users who are admins or find all products above a certain price.