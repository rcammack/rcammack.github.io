---
layout: essay
type: essay
title: Define Design
# All dates must be YYYY-MM-DD format!
date: 2018-04-29
labels:
  - Design Patterns
  - Education
---

Imagine you are faced with a problem similar to one you have previously encountered and successfully resolved. You are aware that the solution you used in the past worked well and is applicable to your current situation. Would you learn from your past experience and utilize (and perhaps modify) the known solution, or would you reapproach the problem from scratch? Clearly, not using the given solution is an inefficient way to go about solving the problem. 

In software design, it is common to encounter identical or very similar problems that can be solved with a common solution. In other words, there often exists a general solution that is applicable to a variety of similar issues and can be used repeatedly in solving these issues. These solutions are commonly referred to as *design patterns*. You can think of a design pattern as a template that serves as the base for solving problems in different situations. There are many different types of design patterns covering a variety of topics including those dealing with object/class structures, creation, and communication. In addition, there are anti-patterns which describe design patterns that should be avoided. 

Design patterns make a software engineer's life easier. They usually make coding a faster, more efficient, and more understandable process. This is because less time is wasted recreating the base of the solution, and since, generally, other people have used the same design patterns, the code is more understandable for them. When describing how an application that follows a popular design pattern works, you will find that people recognize the patterns in your app that they themselves have used before and this helps them to quickly understand your methods. In my experience, design patterns have made it easier for me to understand other people's code since they used similar approaches as me. 

A few specific design patterns that I recognize and have used in my own code include the Prototype, Observer, and Model-View-Controller (MVC) patterns. The Prototype design pattern is fundamental to JavaScript and comes up every time you use prototypal inheritance. The Observer design pattern is useful whenever you want some event(s) to happen as the result of a change of state for a subject. Similarly, the Publish-Subscribe architectural model used in Meteor handles what happens when there's an update to the status of data collections and helps manage the data flow in an application. Lastly, the MVC design pattern separates an application in three separate but interconnected parts: model, view, and controller. For example, in a Meteor application that I have designed, the model is a Mongo database (MongoDB), the view is React, and the controller used the React Router. 

If you would like to read more about specific design patterns, [this article](https://sourcemaking.com/design_patterns) covers a few popular creational, structural, and behavioral design patterns. 
