# Introduction to React and Components 

A component is a modular, portable, replaceable, and reusable set of well defined functionality that encapsulates its implementation and exporting it as higher level interface. A component is also a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. 

## Characteristics of a Component: 

* Reusability
* Replaceable
* Not context specific 
* Extensible 
* Encapsulated
* Independent 

## Advantages of Component-based Architecture: 

Component-based architecture focuses on the decomposition of the design into individul functional or logical components that represent well defined communication interfaces containing methods, events, and properties. It provides a higher lever abstraction and divides the problem into sub-problems, each associated with component partitions. 

## Props: 

*Props* is short for *properties* which refers to properties of and object. 
Props in **React** are inputs that you pass into components. The props enable the component to access customised data, values, and pieces of information that the input holds. 

### Flow

In React, the flow of props is one-directional (top → down)
 * Parent component defines data.
 * Parent pases data as props 
 * Child receives props
 * Child uses props