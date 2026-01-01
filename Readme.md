# Plus One (LeetCode – Problem 66)

## 📌 Problem Description

You are given a **large integer** represented as an array of digits.  
Each element in the array represents a single digit of the number, ordered from **most significant to least significant**.

The task is to **increment the integer by one** and return the resulting array of digits.

---

## 🧠 Understanding the Problem

- Digits are stored from left to right  
- No leading zeros in the input  
- Each digit ranges from `0` to `9`  
- Carry handling is required when a digit is `9`

---

## 🔍 Examples

### Example 1
Input: [1,2,3]
Output: [1,2,4]

**Explanation:**  
123 + 1 = 124

---

### Example 2
Input: [4,3,2,1]
Output: [4,3,2,2]

**Explanation:**  
4321 + 1 = 4322

---

### Example 3
Input: [9]
Output: [1,0]

**Explanation:**  
9 + 1 = 10

---

## 🚀 Approach

1. Traverse the array from **right to left**
2. If a digit is less than `9`, increment it and return the array
3. If a digit is `9`, change it to `0` and continue
4. If all digits are `9`, add `1` at the beginning of the array

---

## ⏱️ Complexity Analysis

- **Time Complexity:** `O(n)`
- **Space Complexity:** `O(1)` (excluding output)

---

## ✅ Constraints

- `1 <= digits.length <= 100`
- `0 <= digits[i] <= 9`
- No leading zeros

---

## 📚 Reference

- **LeetCode Problem:** 66. Plus One  
- **Difficulty:** Easy  
- **Topic:** Arrays
- My LeetCode Profile:
👉 https://leetcode.com/u/gowthamgspatil/

---

## 👤 Author

**Gowtham GS Patil**



## 📸 Problem & Solution Screenshot

<img width="1364" height="628" alt="image" src="https://github.com/user-attachments/assets/f3b1eb63-9048-4a64-9b7b-756a9710bd3c" />

