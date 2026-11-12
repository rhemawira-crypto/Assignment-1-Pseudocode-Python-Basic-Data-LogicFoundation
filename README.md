Online Store Order Analysis
Module: Algorithm & Programming

Covers: Week 1 (Logic Foundations & Web Application Architecture) + Week 2 (Algorithms & System Logic)

Format: Written solution in pseudocode (no specific programming language required)

Estimated effort: 4–6 hours

Purpose
This assignment tests whether you can apply the programming concepts from Module 1 in pseudocode. Data types, operators, conditionals, arrays, loops, functions, and the core algorithms (counting, searching, sorting, filtering, aggregation) all come together in one realistic problem.

Remember: Real-world programming is 80% problem-solving and 20% syntax. If you can solve it clearly in pseudocode, you can implement it in any language.

You will be assessed against the grading rubric at the end — focus on correct, working pseudocode, not on the syntax of a particular language.

The Problem
You are building a small Order Analysis System for an online store. The backend receives a list of orders and must return a summary report. You are given this data:

SET orders = [
  {customer: "Aisha",  product: "Keyboard",   amount: 250,  category: "Electronics"},
  {customer: "Budi",   product: "Notebook",   amount: 35,   category: "Stationery"},
  {customer: "Aisha",  product: "Mouse",      amount: 90,   category: "Electronics"},
  {customer: "Citra",  product: "Monitor",    amount: 1200, category: "Electronics"},
  {customer: "Budi",   product: "Pen Set",    amount: 15,   category: "Stationery"},
  {customer: "Dewi",   product: "Desk Lamp",  amount: 75,   category: "Home"},
  {customer: "Citra",  product: "Chair",      amount: 320,  category: "Home"},
  {customer: "Aisha",  product: "USB Cable",  amount: 20,   category: "Electronics"},
  {customer: "Eko",    product: "Marker",     amount: 8,    category: "Stationery"},
  {customer: "Dewi",   product: "Headphones", amount: 180,  category: "Electronics"}
]

Write a complete pseudocode program that produces the report described below. Build it from reusable functions wherever it makes sense.

📋 Requirements
1. Filter — significant orders. Produce a list of all orders with amount >= 50 ("significant orders").

2. Aggregate — revenue summary. Compute and print:

The total revenue of all orders.

The average order amount (must handle an empty list without dividing by zero).

The highest and lowest order amounts, including which product each belongs to.

3. Group & count — orders per category. Using a dictionary/map, count how many orders fall into each category (Electronics, Stationery, Home).

4. Customer lookup — search. Write a function findOrdersByCustomer(orders, name) that returns all orders for a given customer, and a clear "not found" result when the customer has no orders.

5. Top customers — sort. Compute the total amount spent by each customer, then list customers sorted from highest spender to lowest using a named sort (Bubble Sort or Selection Sort).

6. Combine & report. Produce one clean, formatted final report presenting all of the above.
