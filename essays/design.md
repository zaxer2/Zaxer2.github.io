---
layout: essay
type: essay
title: Design
# All dates must be YYYY-MM-DD format!
date: 2018-11-29
labels:
  - Design
---

What are design patterns?

I have no idea.

I suppose I'd better go find out.

----

It seems design patterns have to do with the core that the program is built around. This is a difficult topic to discuss, because it's usually an unspoken proccess in solo development that matters tremendously in team development.

For example, if I were building a tetris clone, I'd choose how it runs. I could structure the board as a 2d array, with game calculations being performed on the array. Or I could use the game engine, and perform calculations based on objects' physical positions in space. For individual blocks, I could have each "pixel" be a GameObject, or I could have entire shapes be a GameObject. These distinctions are tremendously important, and not compatible with one another. If working on a team, developers need to be on the same wavelength and using the same method in these regards. This is the essence of a design pattern.



----

This essay was developed for ICS 314 on 8/30/2018
