---
title: Javascript Data Types 💻
date: "2020-06-18T22:40:32.169Z"
description: Javascript ultimate guide for beginners. It doesn't contain every single aspect of Javascript so you don't get overwhelmed.
---

## Value Types

To better understand the world we live in, we assign data to everything. There are diffent kinds of data to describe different kinds of things.
For example, we can number our age, tell our name, count our money, or even save a full profile
in our favorite social network with our birth date, school, email and more! The important thing is to know which type of value fits best.

Javascript is a dynamically typed language. This means that when you allocate something, Javascript automatically knows exactly what type of data
you are putting in. So it's important for you to know what type of data you are dealing with.

Let's get started!

## Numbers

In Javascript, numbers can be decimal or floating, like this:

```Javascript
5 // decimal
3.14159 // floating
100000 // a big (but not so much) decimal number
```

In this case, we would use the integer number for age, the floating number for a mathematical operation and a big number could be use for money.

## Strings

They are called strings because they are a bunch of single characters.
In Javascript, you can single quote (' ') or double quote (" ") any text you want.
Your name, last name, a country or a place. Anything that can be named can be put between quotation marks.

```Javascript
'John'
"Doe"
"15 Street Name 01800"
'555-000-1234'
```

There isn't any difference between single or double quote, it mostly depends on
the convention you (or an organization) want.

## Boolean

This type of value is very simple, it's true or false, yes or no. It's important to remember
these words are keywords, and they should never be used rather than to tell if a
condition is met (true) or not (false)

```Javascript
// Do frogs eat insects?
true

// Is Eiffel Tower in the Vatican?
false
```

Of course when programming conditions, they are going to be more complex than that, but I'm trying to make a point.
This is specially useful when you work with boolean operators, and JS is a little tricky on that, as it covers falsey values in a strange way.
But more on that later.

## undefined

This type of value is given to a variable which is declared, but has no value assigned. Let's say I declare my name, last name and age,
I would put something like:

```Javascript
let myName;
let lastName;
let age;
```

Then, the type of all these values would be:

```Javascript
typeof(myName) // undefined
typeof(lastName) // undefined
typeof(age) // undefined
```

This action is known as: ✨ **declare variables** ✨

It's not until we ✨ **assign a value** ✨ to these variables using (=), they take a different type:

```Javascript
myName = 'Eduardo'
lastName = 'Urbina'
age = 26
```

After assigning values, the ```typeof``` operator for each variable would return:

```Javascript
typeof(myName) // string
typeof(lastName) // string
typeof(age) // number
```

## null

Unlike other programming languages, in Javascript my love 💖, you can assing a null value to a variable. We haven't covered variables, but doing this,
will empty the variable and return an object. Objects are not primitive data types, but null is. This is because of a bug in JS, but fixing it would break
major stuff, so they decided to leave it like this. I know it may seem confusing at a time, but we'll catch on with this concept of 'object'.

For now, I'll leave you with this image so you can better understand undefined and null:

![Null vs Undefined](./nullvsundefined.png)

## Symbol

There's a final primitive data type which is Symbol, but I won't be covering it in this tutorial as this is used in meta programming. It is a non-common used data type.
If you want to know further about this. I recommend the following [article](https://www.keithcirkel.co.uk/metaprogramming-in-es6-symbols/?fbclid=IwAR3DLlFcdsLMSqNclnaMruv7zckA5jWJ540-dWPcQtM9AH3KjCE7ZhCvloc)

If you've got any questions don't forget to [tweet](https://twitter.com/eduardourbinajs)
