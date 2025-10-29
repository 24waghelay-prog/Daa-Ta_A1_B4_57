# 🧭 Travelling Salesman Problem (TSP)

## 📘 Overview
The **Travelling Salesman Problem (TSP)** is a classic optimization problem in computer science and operations research.  
The goal is to find the **shortest possible route** that visits each city exactly once and returns to the starting city.

This repository provides a simple **Python implementation** of the TSP using a **recursive brute-force approach** (backtracking).

---

## 🚀 Features
- Finds **all possible paths** between cities.
- Computes the **total distance** for each route.
- Returns the **shortest possible route** and its total distance.
- Easy to modify for different city sets or distance matrices.

---

## 🧩 Problem Description
Given:
- A set of cities.
- A distance matrix, where `matrix[i][j]` is the distance between city `i` and city `j`.

Find:
- The shortest route that visits each city exactly once and returns to the starting point.

---

## 🧠 Algorithm Used
### **Brute-Force (Backtracking) Approach**
1. Start from a fixed city (e.g., city 0).
2. Explore **all permutations** of the remaining cities.
3. For each permutation, calculate the total round-trip distance.
4. Keep track of the **minimum distance** and the **best path** found so far.

This algorithm has a **time complexity of O(n!)**, which makes it suitable only for a **small number of cities** (e.g., 10 or fewer).

---

