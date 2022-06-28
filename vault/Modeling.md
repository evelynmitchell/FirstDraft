---
id: rbacjgokg1bdsy0gyrr64s4
title: Modeling
desc: ''
updated: 1656426417759
created: 1647126945940
---

# What is a Model?

A model is a description of possible states of a world. It describes the shape, but not a particular instance. The shape includes the things of interest, and their relations to each other, but not what they are.

A simple example of a model is something you would have learned in grade school. When you learned how to count, you learned the model which maps numbers to things in the world. The same series of numbers, the natural numbers, could be applied to apples, or blocks or friends.

n = f(items)
where f is a function that maps items to numbers.

## How is it different than a program?

## Why do you want to model before programming?

## What is it good for?

## How do you write a model?

### State charts

### Modeling languages

#### Alloy

#### TLA+ and PlusCal

## What else is a model good for?

### Using a model to write tests

## Using the tests to help write code

## Suggested exercises

Hello World! model
```mermaid
statechart 
* -> start
start -> print("Hello World!")
end -> *

```