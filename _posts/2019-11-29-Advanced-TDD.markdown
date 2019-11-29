---
layout: post
date: 2019-11-29
category: Testing
description: Blog post on Advanced Test Driven Development
---

# Advanced Test Driven Development
&nbsp;

## The story
The workshop had appeared on my radar after I had received a job posting for *Cazoo*; A software company that highly focuses on brilliant development standards.  

After a bit of research on their company, I had found that they were running an *Advanced TDD workshop*  

I knew I had to sign up to this event ASAP, as I am focused on tech + development standards. As well as I am soon to run my own TDD workshops at my workplace.  

&nbsp;

## The workshop

The workshop went straight to the point. Comparing what I understood previously with what I knew of *TDD* and comparing that to *ATTD (Acceptance Test Driven Development)* 

### Traditional Test Driven Development
![test](/img/blog/refactor_loop.PNG)
![test](/img/blog/red_green_refactor.PNG)

Benefits: 
* Good for tackling new difficult problems. (Blind programming)
* You can use TDD to take your time to properly understand the problem.

Disadvantages:
* You end up spending too much time refactoring.
* Sometimes you end up refactoring your code to the point where you did not even need to:
    * Sometimes Mocking/stubbing everything can be an anti-pattern
    * You end up refactoring code that is only ever run by the test suite... The user of the system does not care at all
    * Refactoring without any real business value
&nbsp;

### Outside in Test Driven Development
* Also: Acceptance Test Driven Development [ATDD]  
* Business first view  
* YAGNI [You Aren't Gonna Need It]
* Minimise Entropy  
    * Focus only on the public interface
* Hide Internal Complexity  
* Clean Code, Readability  
* Immediate feedback

![whiteboard](/img/blog/acceptance_TDD.PNG)

* The idea is that, with enough whiteboarding + planning, you will be able to develop your application the first time round.
* Steps:  
1) Do your whiteboarding + planning + requirements gathering  
2) Based of requirements write acceptance tests  
3) Write the code to pass those acceptance tests  
    * This phase often includes many inner TDD cycles