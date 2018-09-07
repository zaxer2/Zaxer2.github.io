---
layout: essay
type: essay
title: Smart Questions
# All dates must be YYYY-MM-DD format!
date: 2018-09-06
labels:
  - StackOverflow
---

##Smart questions

In Raymond's "How to ask questions the smart way", he goes over what constitutes a "smart" and "not-smart" method of asking a question, designed in this assignment for technical website StackOverflow. Today we're going to be looking at two examples of questions asked in StackOverflow, and determine what makes one or the other "smart" or "not smart".

###https://stackoverflow.com/questions/7825055/what-does-the-c-operator-do

The above is an example of a "smart" method of asking questions". So what makes it this way? Well for starters, the header is concise. It defines the problem, "what does x operator do", the language, "c", and the operator, "??!??!". The question could be answered strictly by reading the title itself, making this a clear and concise question all on its own. In the body, the writer goes into more backstory & depth. He provides an example of the operator in use how he found it, and details his efforts on his own in finding out the use of such an operator. He clearly demonstrates he's tried finding helpful resources on his own, and proves himself worthy of having his question read & responded to. On top of that, he uses good grammar and perfect spelling, making his post concise and easy-to-read.

The replies are concise as well. The top comment explains exactly what the symbol represents, and the next comment down gives more backstory into why such a symbol exists.

###https://stackoverflow.com/questions/19632085/how-do-i-store-a-value-that-is-negative-as-zero

Contrasting that with this post, we can see the immediate decline in quality. For starters, there is little or misleading information in the title. There is no information given on the language he is working in, and when he asks to "store" a value that is negative as zero, he's butchering the apparent request of "converting" a negative value to zero. The post body is not much help either. In his description, he reads "the answer is actually negative one but because the answer is negative, the answer is stored as ZERO". What he means is that he *wants* the answer to *turn into* zero. So there is a massive error in the post body, and on top of that, the title and body are oddly formatted such that it is hard to digest. 

As described by commenter Lukas Graf, '"is stored" or "you want it to be stored" as zero? I'm assuming the latter, but had to read your question several times.' The top reply does not fit OP's confusing question, as it recommends use of the max() function. The replies below it point out that OP wants the answer "to be stored". It is not until the second reply that we reach a useful conclusion, with the commenter recommending a conditional expression that *changes* the result to zero *if* it is less than zero. However, not even the solver addressedhe core issues behind OP's misunderstanding, as it was so muddled behind confusing language and poor structure it was hard enough to address the question in the first place.

###So?

So clearly it's important to write a succinct and informative question when asking for help on StackOverflow. However, being a community of geeks with too much free time, there are still users who will bend over backwards for you regardless of your laziness or ineptitiude. On my search, for example, I stumbled across a post which summed up to "how do I write this code", and in which 3 commenters had written entire code blocks for the OP in different ways. But it is certainly far more polite and far better practice to ask your questions neatly and completely.
