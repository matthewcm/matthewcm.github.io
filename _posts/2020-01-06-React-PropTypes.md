---
layout: post
date: 2020-01-12
category: React
description: Learn about React Proptypes
---
 

# React Proptypes

What is it? 

It's an extra bit of validation placed Upon the props of a React Component.

You place the exact type of props you expect to receive as props from your component.

<Component stringProp="I am a string" /> 

At the bottom of the component code, you are able to set the props you are expecting, and the type of those props, as well as if the are required or not. Etc.

Why?
React props provide to you and additional collaborators what your component requires to work, and how the component is expecting. Without this, the programmer will have the read the entire component code to understand what types the props makes sense to be. And it's pretty hard to track all of this. Especially when you have a huge amount of interconnected complex components.

It does not take long to do, and it provides so many benefits. It is like Typescript in a way. But absolutely desired. There is no harm in adding Proptypes too.
