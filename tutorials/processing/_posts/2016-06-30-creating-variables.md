---
layout: tutorial
title: "Creating Variables"
slug: creating-variables
---

In the previous tutorial, we learned about [using variables](/tutorials/processing/using-variables). 

Variables are names that hold values, and we can use a variable anywhere we can use a value just by writing its name. That let's us do things like this:

ellipse(width/2, height/2, width, height);

This program uses the `width` and `height` variables to draw a cirlce that fills up the window.

![circle](/tutorials/processing/images/creating-variables-1.png)

Processing gives us variables like `width` and `height`, but we aren't limited to using only what Processing gives us. We can create our own variables!

## New Syntax

Creating a variable requires some new syntax (this is just another way to say that the code looks a little different from what you've been doing so far), so let's go over that first.

To create a variable, you have to give it a **type**, a **name**, and a **value**.

- The **type** tells Processing what kind of value the variable will hold.
- The **name** is what you'll use later in the code, exactly like you've used `width` and `height`.
- The **value** is the value that you want the variable to hold.

## What are types?

Processing needs to know what kind, or **type**, of value that a variable will hold. There are a few different types to choose from:

- The `int` type holds whole numbers like `0`, `1`, or `-256`.
- The `float` type holds decimal numbers like `0.5`, `3.14`, or `-123.45`.
- The `String` stype holds text like `"Hello world"`, `"Happy Coding"`, or `"Kevin"`. `Strings` are always between quotation marks.

There are other types, but these three will get you pretty far, so let's focus on them for now.

## Creating a Variable

You create a variable by giving it a type and a name, then assigning a value using the `=` operator.

```java
String message = "Happy coding!";
```

This line of code creates a `String` value that holds the text `"Happy coding!"` and stores it in a variable named `message` which we can use anywhere we could use a `String` value. For example, we could pass it as a parameter to the `text` function:

```java
String message = "Happy coding!";
text(message, 10, 50);
```

The `text` function takes 3 parameters: a `String` value (in other words, some text inside quotation marks), and an `x` and `y` position to display it on the screen.

![Happy coding message](/tutorials/processing/creating-variables-2.png)

If you're not familiar with the `text` function, that's okay- you can read more about the in [the reference](https://processing.org/reference/)!

## Using our Variables

Remember our example from [the previous tutorial](/tutorials/processing/using-variables) of drawing a target based on the size of the window using the `width` and `height` variables?

```java
size(150, 150);

fill(255, 0, 0);
ellipse(width/2, height/2, width, height);

fill(255, 255, 255);
ellipse(width/2, height/2, width*.75, height*.75);

fill(255, 0, 0);
ellipse(width/2, height/2, width/2, height/2);
```

This code uses the predefined `width` and `height` variables to draw a target that fills up the window.

We can modify this code to use our own variables instead, so the target is no longer dependent on the size of the window, but is still easy to change:

```java
size(150, 150);

float targetX = 75;
float targetY = 85;
float targetSize = 100;

fill(255, 0, 0);
ellipse(targetX, targetY, targetSize, targetSize);

fill(255, 255, 255);
ellipse(targetX, targetY, targetSize*.75, targetSize*.75);

fill(255, 0, 0);
ellipse(targetX, targetY, targetSize/2, targetSize/2);
```



Let's do something similar, only instead of basing the width and height on the width and height, let's base it on variables that we create

random?

variables have a type, a name, and a value
variables save us time and headaches
do cool things like random

## Homework

Remember your drawing from the previous homework? Instead of basing it off the width and height, change it to draw at a random location and size

Draw it with random colors

Create a shape made from random points

Flowers, smiley faces, cats, unicorns

showing current time?
