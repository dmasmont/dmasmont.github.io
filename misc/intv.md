# Coding Interview Practice

## Problem 1: Two Sum
**Difficulty:** Easy  
Given an array of integers `nums` and an integer `target`, return *indices* of the two numbers such that they add up to `target`.

You may assume that each input would have **exactly one solution**, and you may not use the same element twice.  
You can return the answer in any order.

**Example:**
```
Input: nums = [2, 7, 11, 15], target = 9  
Output: [0, 1]  
Explanation: nums[0] + nums[1] = 2 + 7 = 9
```

---

## Problem 2: Valid Parentheses
**Difficulty:** Easy  
Given a string `s` containing just the characters `'('`, `')'`, `'{'`, `'}'`, `'['`, and `']'`, determine if the input string is valid.

An input string is valid if:
1. Open brackets are closed by the same type of brackets.
2. Open brackets are closed in the correct order.

**Example:**
```
Input: s = "()[]{}"  
Output: true  

Input: s = "(]"  
Output: false
```

---

# Multiple Choice Questions

## Python (3 Questions)
1. What will be the output of the following code?
```python
def func(nums=[]):
    nums.append(1)
    return nums

print(func())
print(func())
```
A) `[1]` and `[1]`  
B) `[1]` and `[1, 1]`  
C) `[1, 1]` and `[1, 1, 1]`  
D) Error  

---

2. Which of the following statements about Python list slicing is **true**?

A) `list_a[::-1]` returns the list reversed.  
B) `list_a[::2]` returns all elements in reverse order.  
C) `list_a[:3]` removes the first three elements from the list.  
D) Slicing always modifies the original list.  

---

3. What is the output of the following?
```python
a = {1, 2, 3}
b = {3, 4, 5}
print(a & b)
```
A) `{1, 2, 3, 4, 5}`  
B) `{3}`  
C) `{}`  
D) `{1, 2}`  

---

## Node.js (3 Questions)
1. What will `console.log(typeof null)` print in Node.js?
A) `"null"`  
B) `"object"`  
C) `"undefined"`  
D) `"string"`  

---

2. In Node.js, what is the main difference between `require()` and `import`?
A) `import` can load JSON files, `require()` cannot.  
B) `require()` is synchronous, `import` is asynchronous.  
C) `require()` only works in browsers.  
D) `import` is older than `require()`.  

---

3. Which statement about the event loop in Node.js is correct?
A) It executes callbacks in the order they are registered, regardless of I/O completion.  
B) It handles asynchronous callbacks after completing the current call stack.  
C) It prevents Node.js from handling multiple requests at the same time.  
D) It runs in a separate thread from the main JavaScript execution.  

---

## AWS (3 Questions)
1. In AWS S3, which storage class is **most cost-effective** for data that is rarely accessed but must be immediately available when needed?
A) S3 Standard  
B) S3 Glacier Instant Retrieval  
C) S3 Standard-IA (Infrequent Access)  
D) S3 One Zone-IA  

---

2. What is a primary use case for AWS CloudFormation?
A) Automating database queries.  
B) Deploying and managing infrastructure as code.  
C) Encrypting data stored in S3.  
D) Distributing content to edge locations.  

---

3. Which AWS service would you choose to run containers without managing servers or clusters?
A) Amazon ECS with Fargate launch type  
B) Amazon EC2  
C) AWS Lambda  
D) Amazon RDS  

---
