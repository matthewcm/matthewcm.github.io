---
layout: post
date: 2020-01-24
category: React
description: Learn about React Redux
---
 

# React Redux



## What is it.

It is a JavaScript library built to cleanly manage state in your projects, it is not exactly a React Specific Library. But mainly used in React projects.

Before hooks came out for React, state management, and data handling was not a clean process. It was difficult, and there was not a clean structured workflow so managing state required for your interconnected react components.

Redux solved this. Handling state between components was made so much easier. Redux creates a global state (a Redux store) that each component is able to view, by dispatching specific actions, and receiving the desired data from the global state as props to the component. Far easier than chaining state from a parent component, to a child, to it's child, to it's child... Chaining Props no more, it is far too difficult to maintain. 


With Redux,  maintaining a projects data handling is so much easier. All the data handling is done in a single place, away from the front end component code. Separating behaviour.


Redux Sagas. An extra library that further separates behaviour. This allows you to further different types of Data handling, simple data handling such as component states such as to show them etc, can be done as normal. But complex data handling actions such as calling an API, that brings back new content, or even modifies the content in the API.

Redux is all about separating concerns, which is a great programming standard to follow.

## Vs Context hooks

What about the new, what about context hooks.

Context Hooks does make state management far easier than using Redux. It also does separate concerns, however not as much as what Redux offers.

Because it is so easy. It is strongly recommended when developing a quick application, or when the application does not have a high frequency of state changes.

However, when the application does have a high frequency of state changes. Redux provides a lot faster performance that context hooks does not yet achieve.

And I personally think that when you do get your head around Redux. The workflow Redux requires to set up new states is such a brilliant process, and really makes sure than in your React Components, you are focusing a lot more in the actual JSX.
