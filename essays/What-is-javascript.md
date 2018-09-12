---
layout: essay
type: essay
title: What is Javascript?
# All dates must be YYYY-MM-DD format!
date: 2018-08-31
labels:
  - Javascript
---

## How do you explain Javascript?

Javascript is, so far, just another programming language. Nothing about it is strikingly unique. It holds the same operators, methods for declaring functions, return parameters, etc. as every other programming language I've worked with so far. The only issues working in Javascript come from translational issues. Int becomes let, string becomes let, and FINAL becomes const. The one thing that sets javascript apart from other languages, I find, is its looseness.

Javascript is far too loose in its syntaxing policy. Or rather, it has a different form of syntaxing, but doesn't seem to care whether you do it one way or another. In Java, for example, the end of a line is declared by the semicolon ";" character. In Javascript, it's declared by the "enter" character. But you can still put a semicolon on the end of your line. Javascript doesn't care, and will seem to ignore it.

In Python, indentation levels are defined by literal indentation, as in how many times you press the tab key before a line. Javascript uses the Java method of defining indentation levels with brackets, but also doesn't seem to care whether you indent or not. Maybe it's just JSFiddle, but where Oracle would automatically put you at the correct indentation level whenever you hit enter, JSFiddle will often boot you to the back of the line and require you to hit tab a number of times by yourself.

Javascript also has a really freeflowing attitude towards variables. A variable can contain whatever, a function can pass whatever, a function can return whatever. This sounds EXTREMELY frustrating to work with, especially on a team, where people might be passing variable types your function isn't ready to expect, or they might be expecting return types your function can't deliver.

## WODS

Wods are... not a good idea. At least not in the current format. Setting a requirement and expecting a program to run within a timeframe is fine, but counting the program as "failed" if it doesn't run within that timeframe is damaging and detrimental to a programmer's health. The reason being, the average programming proccess, as I see it, tends to go one of a few ways.

### case 1:

The programmer develops the program flawlessly. It takes about 5 minutes. This is a very rare case.

### case 2:

The programmer develops the program flawlessly, aside from a small syntax error denoted in the console. Developing, debugging, repairing, and testing, all total about 12 minutes. This is the most common case.

### case 3:

The programmer develops the program, but with a non-syntactical flaw. For example, a + is replaced with a \*, or a variable name is replaced with another, similar variable name. Developing, scouring and tracing the code for the flaw, debugging ,repairing, and testing, all total about 20-30 minutes. This case is almost as common as case # 2.

### case 4:

The programmer flounders and produces utter garbage. This takes any amount of time, depending on when they choose to give up.

## Why the current WOD system is problematic

The idea of racing coders against each other fails to take into account the difference between "good code", "code with 1 bug", and "abhorrent garbage code". Coders who make a syntactical error detectable by the computer often get an A while coders who make a nonsyntactical error that has to be searched for are pinned with an F. This puts your grade entirely on the type of error you make while writing code, and lumps in "people who did amazing but made 1 type of mistake" at the same grade level as "people who have no idea what they're doing". 

### How could it be fixed?

Give DNF'ers an assisted debugging period or just an appeal review. Either they're allowed an extra 5-10 minutes with the TA to trace their code and find where it goes wrong for 50-70% credit, or they're allowed to turn in their broken code as-is for review, and if it's found that they failed only due to a simple bug they're allowed back 40-60% of credit. This way, small bugs don't make-or-break your grade and the coder doesn't start hyperventilating when the code fails to return the expected result.

----

This essay was developed for ICS 314 on 8/31/2018
