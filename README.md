# DSA Solutions Repository

Welcome to my **Data Structures & Algorithms (DSA)** solutions collection.  
This repository contains solutions to a wide range of DSA problems sourced from platforms such as:
- LeetCode  
- GeeksforGeeks (GFG)  
- Codeforces  
- InterviewBit  
- HackerRank  
- Other online resources and coding contests  

Each solution is written with clarity and efficiency in mind, often including explanations or comments to help understand the approach and time complexity.

---

## About This Repository

This repository serves as:
- A personal learning archive for DSA practice  
- A reference for others learning problem-solving and algorithm design  
- A way to track progress across multiple sources and difficulty levels  

All solutions are implemented in **C++ / Java / Python** (depending on the problem or platform).

---

## Folder Structure

DSA-Solutions/


Each folder corresponds to a **topic**, and files are named according to the **problem** they solve.

---

## Topics Covered

- Arrays and Strings  
- Linked Lists  
- Stacks and Queues  
- Trees and Binary Search Trees (BST)  
- Heaps and Priority Queues  
- Graphs (BFS, DFS, Dijkstra, etc.)  
- Dynamic Programming  
- Recursion and Backtracking  
- Bit Manipulation  
- Greedy Algorithms  
- Searching and Sorting  

---

## Problem Sources

- [LeetCode](https://leetcode.com/)  
- [GeeksforGeeks](https://www.geeksforgeeks.org/)  
- [Codeforces](https://codeforces.com/)  
- [InterviewBit](https://www.interviewbit.com/)  
- [HackerRank](https://www.hackerrank.com/)  
- [Coding Ninjas](https://www.codingninjas.com/)

---

## Solution Format

Each solution includes:
1. Problem statement (brief summary)  
2. Approach or logic explained  
3. Time and space complexity  
4. Code implementation  

Example:
```cpp
// Problem: Two Sum
// Source: LeetCode
// Approach: Hash map for complement lookup
// Time Complexity: O(n), Space Complexity: O(n)

vector<int> twoSum(vector<int>& nums, int target) {
    unordered_map<int, int> m;
    for (int i = 0; i < nums.size(); i++) {
        int complement = target - nums[i];
        if (m.count(complement)) return {m[complement], i};
        m[nums[i]] = i;
    }
    return {};
}
```
