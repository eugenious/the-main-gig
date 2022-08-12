---
title: "2 - The Ideal Coding Sequence"
weight: 3
---

_What happens in a perfect situation._

So now we finally get to it, and actually "build the thing". This really and truly is the core activity of the main gig.

With the exception of small side projects or early-stage startups, the ideal coding sequence looks something like this. For each piece of new functionality, a developer should, in sequence:

1. Write the documentation: make it easy for others to know about the feature
2. Write the tests: another form of documentation about the feature
3. Write the code: just pass the tests, and you're done!
4. Refactor the code: make the code better, and clean up after yourself

## Write the documentation

We all hate dealing with undocumented features, and yet most developers hate writing documentation! You might embrace the task, or you might treat it like brushing your teeth. Either way, just do it! Getting good at writing documentation is getting good at communication in general, and if there is one soft skill that every successful developer should have, it's being good at communicating, in all its various forms.

Yes, in fact, there is such a thing as documentation driven development, but it's generally not widely practiced. Perhaps it should be. If you are starting with reasonable requirements already described in the ticket, you're already half-way there! Writing documentation includes deciding how much is actually needed and where the documentation needs to live, be it in a user guide, an automatically generated API spec, a README file or as comments in the code.

Whereas requirements in tickets are often treated as ephemeral, the documentation has a lifecycle that aligns with the lifecycle of the application, or at least, the particular feature.

## Write the tests

Test driven development (TDD) and behaviour driven development (BDD) are well-known ideas, so we won't deal with them in detail here.

There are many great books and resources written about testing, and you are encouraged to pick up a few of the classics in the software development literature and read them.

Writing code is hard! Writing test code is even harder! But when you run your suite of automated tests, and they all pass, you will know that everything is right with the world (the world of your application, that is). 

In today's software world, having suites of automated tests are table stakes.

## Write the code

We've come to the special moment where the new feature gets implemented! At this point the test you've written is failing. You implement the feature by writing code to pass the test, and you're done. You have an excellent understanding of the functionality you need to write, because of all the effort you've put into writing the test for it. And when that test passes, you have evidence that proves your code works correctly.

## Refactor the code

There's working code, and there's great code. If you stop now, you will have working code. But take it a step further! An experienced developer is always mindful of technical debt and code legibility. The mantra to live by is "always leave it better than you found it". And so the classic TDD sequence: Red (failing test), Green (passing test), and Refactor (improve implementation).

What if you can't tell good code from bad code? It is a legitimate problem.

The unfortunate reality is there is a lot of bad code out there. If you are a budding software developer you actually have to go out of your way to look for good code to study, and it's only after looking at lots and lots of code, do you begin to be able to discern good code from bad code. You start detecting code smells. When you are just starting out as a developer and you encounter code you don't understand, you probably think to yourself, "this is some fancy code, I must not be smart enough to understand it". Complexity impresses you, complexity is delicious. Once you become a seasoned developer, and you encounter code you don't understand, you likely might think to yourself, "this is some fancy code, whoever wrote this got their knickers in a twist". The best developers write the most obvious code, which anybody could have written, it looks so simple. Code perfection, like perfection in other fields, looks effortless to the untrained eye. But most likely, that perfect-looking code was the product of much wise refactoring.

## But it doesn't work that way!

It is called the ideal sequence because the bar is set impossibly high. It is exceedingly rare to execute the sequence flawlessly from the first step to the last, except on the tiniest of features. 

A more realistic picture of the process of coding goes like this. You think a little bit about the tests, you experiment with some code, you realize that to implement your new feature cleanly, some refactoring of the existing code is desired, you go back to the product owner to clarify something missed in the requirements, you finish the code, you finish the tests, then, oh yeah, you forgot to write the documentation so you do that. 

Why bother describing the ideal sequence, if it is never to be achieved? Well, primarily to express a mindset. Actually, two mindsets.

The first mindset is that producing quality software means a lot more than just writing the code for the feature. The second mindset is that the process of writing the documentation and the tests is often extremely beneficial to helping you understand the problem space of the feature you are implementing. Software development is very hard, and we can all use all the help we can get!

The mindset of a junior developer and that of an experienced developer is a world apart.

Junior developer: I'm so delighted, I got it working! It's a complex beast, and I'm not quite sure why I needed that line of code there, but I found it on Stack Overflow.

Experienced developer: I'm so delighted, I got it working, and the code looks beautiful, and the tests prove that it works, and the documentation describes how to use it.
