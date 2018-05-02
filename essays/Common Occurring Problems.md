---
layout: essay
type: essay
title: Common Occuring Problems
# All dates must be YYYY-MM-DD format!
date: 2018-5-1
labels:
  - Design Patterns
---

Humans are known to be the world's best pattern-recognition machines. Because we as a species excel at this, ideas like design patterns in computer science are a thing. Even koalas who are less developed cognitively, use pattern recognition to find and consume eucalyptus leaves. What is the idea of a design pattern? It is the ability to create a reuseable solution for a commonly occuring problem. Our cognitive ability to notice that we have seen the problem before allows us to create these solutions for repeated use. 

Everyone I know today has a netflix account. Subscribing to a service like netflix resembles a design pattern I encountered in my project aptly called  publish/subscribe design pattern. Meteor is pretty much built on this idea. This is how it sends and reviece data. In my project where I needed to talk to the database and have it return only information that a specific user should see is the same idea of where two different people subscribed to one thing (e.g. netflix), should only see information relevent to them (e.e. top picks, recently watched).

In the office I work at, we all share the same microwave. This is another metaphor for the singleton design pattern which is basically having global variables that can be used anywhere in the code. Block scoped variables would be like everyone haveing their own microwave for personal use. In my project, the collections I made in the database use this design pattern because they can be accessed from anywhere in the code.

In conclusion, design patterns are important because if you recognize the problem you need to solve, there are probably proven solutions to solve them. The act of recognizing which problem you have and what solution to implement is important to prevent errors and speed up development time. 
