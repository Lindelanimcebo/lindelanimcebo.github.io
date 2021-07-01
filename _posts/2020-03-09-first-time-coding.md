---
layout: post
title:  "First time coding nightmares [for beginner programmers like me]"
summary: "Some advices to people who have just gotten into the world of programming without any prior knowledge"
author: lindelani
date: '2020-03-09 1:35:23 +0530'
category: code
thumbnail: /assets/img/posts/code.jpg
keywords: code, python
usemathjax: true
permalink: /blog/first-time-coding/
---

I started coding in 2018 when I got to UCT. Before then I was doing a subject called CAT (Computer Applications Technologies) in high school. The subject taught us mostly the theory of computer technologies and computer applications such as document processing and HTML. And so with a bit of googling, I was inspired to learn coding but, that did not work out, and so I had to wait for UCT, and fortunately I got to UCT.

During introductory lessons, I felt like this is really fancy HTML, I thought I had an advantage because I did a bit of “coding” in HTML. Turns out, I was thoroughly misleading myself, “HTML is not programming and I repeat HTML is not programming”. on that note, I realised I was screwed and I did not know whatever the hell was going on in class.

My first language was my darling Python through the UCT CSC1015F course/module . It really confused me at first. The syntax was weird, the logic was not making sense. I remember I struggled understanding this little code to reverse a string using a for loop:

```python
string = "My computer"
stringRev = ""
 
for i in string:
     stringRev = i + stringRev
```

Firstly, why the hell is “i” being added before string_rev? How is this thing even working. That was a bit stupid yes, but I got through it, and if you’ve just started as well, you will feel stupid at some points, which is fine really, it’s ok to be stupid. Just keep learning and asking questions, doing practice problems, eventually you will get used to it.

What I really wanted to get to was the problem solving strategy. Many or some of us, when we think of computer science, we think it’s more like those hackers from movies (“The faster you type the better the code is”). Well, no. Computer science is mostly about solving problems, to solve similar problems so that the solution can be used to solve similar problems and other recurring problems, normally with the application of Mathematics and computing.

And so, realising this and looking back to the first chapter we learnt in class – Algorithms, I noticed, it’s not only about the code, and writing it, it’s about having a solution to the problem, and code is really just a tool to efficiently implement your solution. However knowing what to write, when and how, also what is it doing exactly is vital. With these in mind I started developing a strategy ( which I should have developed earlier honestly ) namely PLANNING.

## PLANNING applied to CSC1015F in 2018

* Read and understand the question obviously
* Think of how you can solve the problem without thinking of code at this point
* Draw up your algorithm to solve the problem, you can use text or block diagrams, but the point is, your IDE is not doing anything for now.
* Look out for key words in your algorithm, and translate it to pseudo code. E.G : loop through all numbers = for loop.
* Verify your pseudo code in your head, the translate it to Python code, still on paper.
* Be Python3.10 and interpret your hand written code.
* Once you are satisfied with your code, put it on your IDE, run it, get a few syntax errors, fix them then you are sorted.

### Why the hell would anyone go through that pain?

Well, firstly because I am a slow learner, secondly because in tests and exam, code is hand written. Thirdly, this helped me avoid logic errors which would normally take days to fix, reducing the time I spent on assignments to 2 hours as compared to 5 days. Fourthly, it made me feel powerful.
