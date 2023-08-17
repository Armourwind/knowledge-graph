---
uid: 20230817234203
aliases: 
 - 数组
 - array
type: concept
Category: 
tags: ["#repetition"]
---

## Definition

-  An array is a **linear list** [[data structure]] that uses **contiguous memory spaces** to store a set of data of **the same type**.

## Advantage
- **Random access**  We randomly access the elements in the array by subscripts, with which the address can be easily computed via the addressing formula. Time complexity is **O(1)**.

## Disadvantage
-  **Contiguous memory space**  In some cases where the memory space is *fragmented*, arrays are not suitable.
- **Low effective deletions and insertions** To ensure data continuity, every time an element is deleted or inserted, all elements behind or in front of it need to be moved forward or backward by one position.
****
> [!caution]
> **Avoid accessing arrays using out-of-bounds indices.**
## Commonly used [[algorithm]]


## Applicability


## Known uses



****
>[!question]
> **Why does the index of an array start at 0 in many programming languages?**
> - ***Historical reasons*** According to the C convention, in many C-like languages such as Java, C#, C++, the array index starts at 0.  Instead, Python could start with a negative number.
> - 



