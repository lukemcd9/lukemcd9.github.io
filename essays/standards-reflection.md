---
layout: essay
type: essay
title: Standardization
# All dates must be YYYY-MM-DD format!
date: 2019-09-26
labels:
  - Software Engineering
  - JavaScript
  - ESLint
---
## Best Practice

After working with ESLint for a week, I've come to find that coding standards are great and everyone should try to adopt a standard even if it's not ESLint. Having a standard allows everyone's code to look similar and forces software engineers to use the best practice for the language. For example, with ESLint if you define a variable with ***let*** that is never reassigned ESLint tells you that it should be a ***const*** which is pretty useful so the variable isn't accidentally reassigned later which could cause something unexpected to happen in the program. The only thing that I'm not a fan of in ESLint is the spacing recommendations  those mostly seem tedious and aren't necessarily insanely important to me personally, but since it can help in other things that aren't just spacing I'll deal with it as it's for the best that I follow the rules.

## Working In Teams

Standards help significantly when working with a group of software engineers on a project. Since everyone has their own style of coding, forcing a standard allows everyone to be able to read someone else's code without having to figure out someone else's style of coding. Currently the projects I work on have a standard that we have to follow, and we have to make sure before committing that the code is formatted to the standard. ESLint is superior to what I use at work as it integrates with IntelliJ seamlessly and it gives warnings and errors while you're writing code. What I use for work is just a formatter, so once I developed my code I have to run a code reformatter that will attempt to format it into the loaded format which doesn't always work.

Overall, I think ESLint is a great standard to follow. Even though at times some of its warnings are tedious, it's for the greater good. Using ESLint allows me to learn the *best* practice which hopefully I'll eventually write by default and I won't need to rely on ESLint as much. I prefer ESLint now to other ways that I've been using to follow coding standards.
