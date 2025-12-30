# 🎂 Birthday Probability Problem
![Birthday Probability Illustration](assets/birthday_problem.png)

This project demonstrates the **Birthday Problem**, which computes the probability that **at least two people share the same birthday** in a group.

The idea is to calculate the probability that **all birthdays are different**, then take the complement.

P = (365/365) × (364/365) × ... × (365 − (n − 1))/365

A simple Python loop multiplies these terms to estimate the probability.

With only **23 people**, the probability of a shared birthday is already **greater than 50%**.
