# PB - Classes - Basics

This task is all about practicing the very basic concepts of classes. Let's practice using the `Date` class that is built into JavaScript!

Add your answers directly into this file.

```js
    const now = new Date();
    const test = new Date();
```

1. In the code above, what is the `now` variable?
> It's an instance of Date.

2. What is the type of the `now` variable?
> 'object'

3. In the code above, what is the `Date`?
> A built-in Class

4. What is the type of `Date`?
> 'function'

5. What do you get when you do `console.log(now)`?
> '2021-11-19T14:54:04.171Z'

6. What do you get when you do `console.log(Date)`?
> [Function: Date]

7. What do you get when you do `console.log(new Date())`?
> 2021-11-19T14:55:44.754Z

8. Is `now` truthy?
> It sure is! :D

9. What do you get when you do `console.log(now === test)`? Why?
> false, they are different instances of the Date class with different internal data

10. What do you get when you do `console.log(now === Date)`?
> false

11. What do you get when you do `console.log(now === new Date())`?
> false

12. What do you get when you do `console.log(new Date() === new Date())`? Why?
> false, we are creating two separate instances of Date, both with their own separate internal data and identity