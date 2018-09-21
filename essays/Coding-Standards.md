---
layout: essay
type: essay
title: Coding Standards
# All dates must be YYYY-MM-DD format!
date: 2018-09-20
labels:
  - JSFiddle
  - IntelliJ
---


## Coding standards

Why do we use coding standards?

### Pros

Coding standards help a workplace all function on the same track

Coding standards help ensure your code is well formatted as per some general standards that are universal among most coding standards

Coding standards make your code utilize functions consistently, instead of haphazardly combining different functions that do similar things

### Cons

Coding standards can be hard to learn

Coding standards can impede progress by presenting otherwise unneccessary challenges

Coding standards take away focus from the presented logical problem and put that focus into adhering to formatting rules

Coding standards are not flexible, and care more about adhering to a rigorous syntax than being digestible

## Let's talk about that.

We use coding standards for, seemingly, one major reason: to make our code readable. There are applications where that is a useful attribute to have, but also a number of situations under which that fails or is otherwise the less important end goal. 

The problem, at its core, lies in that coding standards as a whole are just another rigorous syntactical hoop to jump through in your programming, rather than an adaptable check of whether the code is "digestible to a person". That syntactical hoop might rear itself in an in-depth project, such as programming a full game of tetris, wherein working through the logic of a tetris board is an extremely difficult task that's only exaserbated by your editing program complaining about you concatenating strings with the "+" operator rather than the "${}" operator. Or your programming having no extra lines at the end of the function. Or your programming having too many lines at the end of the function. These things will largely not affect your code's readablitiy to yourself or anyone else, but may have a large impact on your morale to continue working on such heavy logical processing.

This, of course, isn't a problem if you've learned and adapted the coding standards long before you try to jump into such heavy processing. But trying to learn coding standards alongside learning a type of code ushers in a whole host of new issues. Firstly, googled solutions may not be compatable with your coding standard. Say you want to learn how to concatenate strings, and a StackOverflow post tells you to use the '+' operator. You set it up, but it still throws an error, this time one from your coding standards controller. This will hurt to see, force you to rewrite a bit of code using a method you're not familiar with, and cause you to lose trust in your #1 resource: community forums.

## So when & how should coding standards be implemented? 

Firstly, coding standards should not be a part of the first time you learn a language. You should be able to make these building blocks on your own, and then modify them later to a standard. That has been my experience so far in the JSFiddle to intelliJ migration, but I still have classes (such as C in ICS212) where they are making you learn a language at the same time as enforcing an arbitrary set of coding standards for that language, which is frustrating and counterintuitive for the reasons listed above. 

When it does come time to implement your coding standards, however, I think it should be done thusly:

### Have your editor automatically implement coding standards where possible.

For things as simple as "{ on new line", just have the editor automatically make that correction when it is encountered.

### If not that, then have your editor suggest a correction where possible.

If your operators were flipping around and morphing themselves automatically after being typed, it would be extremely jarring and hard to understand as a programmer. Instead, for things like "prefer ${} over +", it should be flagged and given the option to automatically correct itself.

### Save certain errors for the manual check, rather than checking at all times.

Trying to betatest a program and constantly getting flags like "you declared a variable that wasn't used!", or trying to write a function and immediately after opening your brackets getting a red flag "you declared a function that wasn't used!" are all immensely frustrating flags to contend with. These "cleanup" practices, wherein you take out loose ends that never got tied together in finished code, should ONLY be checked for when your code is COMPLETELY finished, to avoid frustration. A simple "check code as completed" button, that highlights just the coding standard errors like this, would help immensely.
