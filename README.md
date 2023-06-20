# Expense Tracker
> A budgeting and expense tracking app. Using Redux Toolkit.

Live demo [expansetracker_simonapiz](https://expansetracker_simonapiz.surge.sh/). <!-- If you have the project hosted somewhere, include the link here. -->

<img src="https://github.com/SimonaPiz/ExpenseTracker/assets/91121660/696fccaa-cec2-4ae1-8bdc-d34d34a0fc5a" alt="preview" title="preview app" width="700px"/>

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Author](#author)
* [Acknowledgements](#acknowledgements)

## General Information

The app allows users to set budgets for various categories, such as food and transportation, and track transactions in those categories. It then sums their spending in each category to calculate the amount of money that remains to be spent.

Refactoring with Redux Toolkit, using a slice-based approach to produce the app’s actions and reducers.

## Features
### The application :
- should display budgets for various categories
- allow the user to update/set budjets

<img src="https://github.com/SimonaPiz/ExpenseTracker/assets/91121660/9469577b-c821-487d-bb56-da93eaae7198" alt="Tracker preview" title="Tracker preview" width="500"/>

- should display track transactions
- allow the user to delete each transaction

<img src="https://github.com/SimonaPiz/ExpenseTracker/assets/91121660/0cc508fa-347e-4b2b-960d-529f5f782a49" alt="transactions preview" title="transactions preview" width="500"/>

### In "new Transaction" component:
- the user can add many transaction for each categories
  - he can choose the categorie
  - add a description
  - add the amount
 
<img src="https://github.com/SimonaPiz/ExpenseTracker/assets/91121660/18d89426-5965-42b5-a866-aa69343401ea" alt="Add transaction preview" title="Add transaction preview" width="500"/>

## Technologies Used
- Node - version 18
- React - version 18
- Redux - version 4
- reduxjs/toolkit - version 1.8

## Setup
To run this project, install it locally using npm:
```
$ cd ../[directory]
$ npm install
$ npm start
```

## Author
[Simona Pizio](https://github.com/SimonaPiz)

## Acknowledgements
This project comes from the [Codecademy's Front-End Engineer](https://join.codecademy.com/learn/paths/front-end-engineer-career-path-b/) course.
