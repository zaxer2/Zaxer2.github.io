---
layout: project
type: project
image: images/chatbot.PNG
title: Covid Chatbot
permalink: projects/chatbot
# All dates must be YYYY-MM-DD format!
date: 2020-11-11
labels:
  - Java
summary: A Covid-19 assistance bot made for HACC 2020
---

The 2020 Hawaii Annual Code Challenge was held online, due to COVID restrictions. Whether or not this was an unusual circumstance is beyond me, as this was the first HACC in which I participated. It was a rocky ride, to say the least. I did not feel able to connect with the peers present at the event, and did not find myself able to communicate with anyone participating regarding team formation or collaboration. As a result, I took on this HACC project solo, and it was an interesting experience.

The 2020 HACC had several assignment types to choose from, and as a solo programmer on a team of one, I had my free reign of choice over which project I would tackle. After attending the orientation and reviewing the options, I had several days to mull over the projects and choose. Some were outside my technical scope, some just gripped me less than others. In the end, I settled on the project I had been mulling over the most: the COVID-19 Chatbot.

The assignment of the COVID-19 Chatbot was to be an informational tool for the state of Hawaii: A public-facing UI with a malleable backend that would allow employees of the state to input COVID-related information and present the public with digestible responses to COVID-related queries. This would have to rely on one method of Chatbot integration, and I began my research into the available Chatbot implementation methods.

Chatbot implementations conventionally split into three different tiers: Menu-based, keyword-based, and contextual. Contextual chatbots would be the most advanced, being dependent on an understanding of sentence structure, objects and subjects, and sophisticated grammar parsing. Keyword-based chatbots, on the other hand, proved much more digestible, since such an implementation involves only parsing for critical words present in a sentence.

Moving on to the implementation, I began my work in Python but eventually converted to Java to maximize efficiency. Implementing a keyword recognition algorithm from scratch proved an interesting and engaging challenge, and designing a backend and text response format was an exciting process that proved to me how much life could be brought to a simple text UI. Unfortunately, as this project was a solo endeavor, I could not completely fulfill my original intended scope. While the text-based functionality of the chatbot works to the best of my intent, there is no surrounding UI encompassing the project. One could call this a feature, however, as it is in its current state malleable enough to be implemented into nearly any website design.

At its core, the Covid Chatbot is designed with two key principles in mind: Display the most relevant information for the given keywords, and avoid repeating yourself. Bots that do not adapt their behavior over the course of a conversation frustrate me, and the Covid Chatbot works as such. Any time a keyword is picked out, the associated text blurb and external resources are queued up. If, however, this keyword has already been discussed, and other keywords are present in the dialogue, the previously-discussed keywords are dropped and only new topics are acknowledged. This prevents the kind of situation where subsequent questions like:
“What kind of COVID mask should I get?”
“Where can I go to get a COVID test?”
“What are the symptoms of COVID-19?”
Trigger redundant responses containing base-line information about COVID-19.

The Covid Chatbot, despite some of its challenges and setbacks, proved an interesting challenge and an engaging process in participating in the HACC 2020. Although I would have preferred to work on a more endeavour project in a larger group, taking on this one solo allowed me the creative freedom to work on something personally interesting and engaging, and I’m happy with what I’ve created as a result.

Click the link below to watch the demonstration video!
[![Watch the video](https://img.youtube.com/vi/uFPu0yLhMAg/maxresdefault.jpg)](https://youtu.be/uFPu0yLhMAg)


This project was developed for the 2020 Hawaii Annual Code Challenge, a coding competition in Hawaii where students compete to develop technical solutions for Hawaii government specifications. It was developed solo by William Cole, in the competing group "TTPI".
https://hacc.hawaii.gov/

Source: https://github.com/HACC2020/TestTeamPleaseIgnore

