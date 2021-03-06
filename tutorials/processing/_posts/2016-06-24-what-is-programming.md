---
layout: tutorial
title: What is Programming?
slug: what-is-programming
thumbnail: /tutorials/processing/images/input-10.gif
tagline: Get ready to write some code.
sort-key: 100
meta-title: What is Programming?
meta-description: Before diving into the code, let's talk about the terms we'll be using.
meta-image: /examples/processing/arraylists/images/random-walkers-3.png
tags: [tutorial,processing,basic]
---

The Processing tutorials teach you how to write code in order to make your own programs. But before we dive in, let's define some of the terms we'll be using.

## What's a program?

A program is a set of instructions that interact with a computer. You probably use programs every day. The web browser you're viewing this tutorial on is a program. Your email client is a program. Games, data visualization, music and video players, these are all programs. These programs are really just a set of instructions that tell the computer what to do- think of a program that instructs the computer to display content from a website, or a program that instructs the computer to play a music file.

Computers can't understand English (at least not yet), so these instructions are written in a language that computers can understand. We call this type of language **code**.
 
## What is programming?
 
We know that a program is a set of instructions that tell a computer what to do, and we know that those instructions are written in code. Programming (also called **coding**) is the process of writing that code.
 
## What is code?
 
Just like there are a bunch of different human languages, there are also a bunch of different kinds of code languages. Different code languages are good at different things: if you wanted to create the server part of a website, you might use Java. If you wanted to write low-level drivers that interact with hardware, you might use C++. If you wanted to create an interactive website, you might use JavaScript.

We'll be using a language called Processing.

## Why Processing?

Processing is designed to make it really easy to create interactive, visual programs without requiring a ton of [boilerplate code](https://en.wikipedia.org/wiki/Boilerplate_code) (a bunch of code that you have to include just to get started, which is super annoying). This makes Processing *fun* and *easier*, and it means we can get started making the kinds of programs that most people want to create. Compare that to many languages that force you to work though the basics though text-based programs via the command prompt, gross!

## What if I want to learn Java or JavaScript?

Another thing I love about Processing is that it serves as a great stepping stone to other languages, especially Java and JavaScript.

Processing is built on top of Java, so it shares mostly the same syntax. And you can deploy your Processing code as JavaScript using [Processing.js](http://processingjs.org/) or [p5.js](https://p5js.org/). You don't really have to understand what I'm talking about, but the point is that learning Processing makes it easier to learn Java or JavaScript.

So if your eventual goal is to learn more complicated languages like Java or JavaScript, that's completely fine. Learn the basics in Processing, and then "graduate" to more complicated languages if you need to.

## Download Processing

You can download Processing from [here](https://processing.org/download/). It's free, so you can click the `No Donation` checkbox for now. If you end up loving Processing, feel free to come back and donate some money. But for now, let's just download it.

The download gives you a `.zip` file. Double click the `.zip` file and then drag the directory inside it anywhere. (For now, putting it on your desktop is fine.) That gives you a directory, and inside that directory is a `processing.exe` file (or a similar runnable file on Mac and Linux). Run that file!

That opens up the Processing editor, which looks like this:

![Processing editor](/tutorials/processing/images/what-is-programming-1.png)

This is where we'll be writing our code. This is a **code editor**, which is a lot like a basic text editor except it has extra features like coloring the text so it's easier to read code, and the run button (the triangular button in the upper-left corner) that runs your code.

In your Processing editor, type this line of code and hit the run button:

```java
ellipse(50, 50, 75, 75);
```

And you should see this:

![circle](/tutorials/processing/images/hour-of-code-1.png)

You can also run the code directly in the browser using this embedded editor:

{% include codepen.html slug-hash="oBdOMy" height="175" %}

Congratulations, you just wrote your first line of code! :tada:


## Homework

Over the next couple days, think about these questions:

- What programs do you use? What types of things do they tell the computer to do?
- What have you heard about different programming languages?
- What types of programs are you hoping to create?

## Next: [Let's write some code!](/tutorials/processing/calling-functions)
