---
layout: essay
type: essay
title: Where's the scope?
# All dates must be YYYY-MM-DD format!
date: 2019-09-06
labels:
  - Software Engineering
  - JavaScript
---
## Dynamically vs Statically typed

If you're coming from the University of Hawaii ICS ciricculum JavaScript can be very weird since mainly Java, C, and C++ is taught which are all statically typed languages. Which means every time you declare variables, functions, or classes you have to specifically say the type that it is for instance:

```java
int x = 0;
float y = 3.14159;
```

Going from having to explicitly type the variables' types to not even worrying about it is really hard at first. When I first was learning JavaScript I had to force myself to assigning different data types to the same variable. It was weird not having my IDE scream at me complaining it's the wrong type. I think overall dynamically typed languages have the upperhand because if you're just learning how to program it's a lot easier to learn since it's almost like reading Math and you don't have to remember the type. For example:

```js
var x = 0;
var y = 3.14159;
```

## Differences from Java

Besides being dynamically typed there's some differences of JavaScript compared to Java. Some differences are variable scope, the ***var*** keyword doesn't restrict it's scope. It allows you to access that variable from anywhere. That just seems ridiculous to me coming from a Java point of view. There also doesn't seem to be any sort of access modifiers. ***Arrays*** can be any type of data integer, float, string, object, another array, you name it. Coming from Java that just seems ridiculous, but after I got used to it, I didn't want to go back to Java's ancient ways. The biggest thing to me that was completely different from a Java perspective is how many useful functions there are that solves a bunch of needed things that I'd have to write myself in other programming languages. When dealing with arrays having methods like ***push*** and ***pop*** is pretty helpful, but I'm still skeptical with liking JavaScript.

## ES6 Improvements

After going through ES6 tutorials, I think I've finally come to terms that I like JavaScript. ES6 introduces so many improvements like finally having scope restriction with ***let***, read only variables with ***const***, arrow functions, destructuring, template literals, and more. ES6's improvements make me not want to go back to using previous versions. It almost makes me not want to go back to another programming lanuage either because of how much little time savers there are. It's way faster to write an arrow function compared to a standard one. Doing string concatenation is a thing of the past with template literals which I think is a big improvement.

## Athletic Software Engineering

Athletic software engineering is a really interesting form of teaching. Personally, I think it's a cool idea and a great way to learn because with most ways of teaching programming you learn syntax, but not the actual application of what you learned. If I was still working as a teaching assistant in a computer science class I would reccommend to the teacher to try out the athletic software engineering approach in order to make sure that the students can actually apply what they learn. I personally don't like the style of teaching that you're basically just seeing how much you can remember rather than actually applying what you learned. With the athletic software engineering it teaches us skills rather than regurgitating things we can remember.
