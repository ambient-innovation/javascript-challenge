# Ambient Innovation Javascript challenge

## Introduction

Welcome to the Ambient Innovation Javascript challenge. This is a small challenge designed for our future employees and 
friends. 

Please implement a small web application that satisfies the below product idea and user stories using React or Angular 
as technology. Please try to implement this in the highest code quality possible. It is more important that the code
quality is very high than that all user stories are implemented. 
In order to do this, please fork this repository, implement your solution and create a pull request. We will then review
your solution and provide feedback.

## Product idea

We have a very nice kitchen in our office, which is used in high frequency by our colleagues to prepare delicious 
meals. We have two fridges and each colleague can put his groceries in either of the fridges. Sometimes it happens,
that I forget which groceries I put in the fridge and when I go to buy new groceries for the next delicious sandwich, 
I am not sure whether I still have some of the ingredients in the fridge or whether I used them up or they expired. 

In order to solve this problem, we want to develop a web application with a list of my groceries in the fridge. 
As an employee of Ambient Innovation, I can visit this web application and maintain my own list of my groceries in the
shared fridges. Below you find a description of the required features: 

## User Stories

- After I bought groceries in the supermarket, I want to add each of the purchased items to my personal list of 
groceries, that are currently in the fridge. For each item I want to enter a name (e.g. "bread", "cheese", "butter"),
and in which fridge I put it ("Fridge 1" or "Fridge 2"). When I enter an item and another item with the same name already exists in the list, I do not want to create an additional entry. Instead I want to increase the amount of this item (e.g. "bread (2x)").

- I want to see a list of all of my items that are currently in either of the fridges. For each item I want to see the 
name.

- I want to be able to mark an item as "used up" after I have used all of it. If I have more than one of this item, 
the amount should be decreased. If I only have one, the item should be deleted from the list. 

- I want to be able to maintain a second list of items, that I still need to buy (a shopping list). The items in this
list also have a name and amount but no association with a fridge, since I have not purchased them yet. When I 
bought one of the items on the shopping list, I want to mark this item as "purchased". It should then move from the 
shopping list to the fridge list.
