# Binary Search

## Prerequisites

You should have a good understanding of [Arrays](../data_structures./arrays.md) before looking at Binary Search.

But, this is a great entry-level algorithm to start with!

## Introduction

Binary Search is an algorithm for searching a sorted array.

Imagine you were searching a shelve of books, sorted alphabetically by title. A good place to start would be the middle of the shelf, and if the book you are looking for is there - great! If no, you can look to the left or right of the title in the center, based on whether the title you are searching for appears before or after that book, alphabetically. Then repeat this loop until you find the title you are looking forward.

This is a binary search approach.

## Study Areas

The best way to learn binary search is to simply try to code it out!

Write a program that does the following:
1. Takes a sorted array, and a target value
2. Finds the value at the middle of the array - if this equals the target value, return the index of this element.
3. If it does not equal the target value, you'll need to either 'go left' if the mid value is higher than the target value, or 'go right' if the mid value is lower than the target value.
4. If you are going left, find the element is at the mid point between the previous mid point, and the left-most element in the searchable area.
5. If you are going right, find the element that is at the mid point between the previous mid point and the right-most element in the searchable area.
6. Repeat this process until one of the following happens:
* you find the target value - return the index of that value. 
* the point for the left-most element in the current portion is higher than the right-most index. This means the target value is not present in the array. Usually, return -1.

_Tip: you'll need to use two-points to keep track of left and right_

Additional Study Points
- [ ] Try to implement binary search using recursion
- [ ] Express the time taken to run binary search elements in terms of `n`, where n equals the number of elements in the sorted array.

## Practice Problems

There aren't many 'pure' binary search challenges, but if you see a sorted array then there's a good change binary search will help you solve the problem!

- [ ] [Search Insert Position](https://leetcode.com/problems/search-insert-position)
- [ ] [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays)
- [ ] [Missing Number](https://leetcode.com/problems/missing-number)

## Resources

- [Interview Cake Binary Search Article](https://www.interviewcake.com/concept/python/binary-search)

There are absolutely loads of YouTube videos on Binary Search - keep looking until you find one that resonates with you. 

There are also plenty of blog posts and articles explaining this. Again, if one resource is difficult to understand, just look for another one.

## Next Steps

From here, you can look at two other searching algorithms for trees & graphs, Depth First Search and Breadth First Search _(content coming soon)_.

