# Heaps

## Prerequisites

You'll need to be familiar with [Binary Trees](./binary_tree.md) before looking at Heaps.

## Introduction

Heaps are a form of binary tree with a special property: 

* In a *Min Heap* the smallest value is always at the Root.
* In a *Max Heap* the largest value is always at the Root.

We'll focus on a Min Heap in this guide.

This means that in a Min Heap, every node is smaller than its children. Because of this, the smallest value is always easily accessible, at the top of the tree. 

As with all other binary trees, Heaps can be represented using an Array.


## Study Areas

- [ ] Be able to describe the 'bubble up' approach to adding new items to a Heap.
- [ ] Be able to describe how a heap is re-balanced after the smallest item is removed.
- [ ] Describe the time complexity of the following actions: get min value, remove min value, insert value
- [ ] Describe what is meant by the term 'heapify'
- [ ] Draw a diagram of 10 unique integer values in a Min Heap
- [ ] Try to build your own Heap implementation

## Practice Problems

Most of these problems involve using an Array as a Heap, which is a common approach to Heap problems

- [ ] [Last Stone Weight](https://leetcode.com/problems/last-stone-weight)
- [ ] [Relative Ranks](https://leetcode.com/problems/relative-ranks)
- [ ] [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/)

## Resources

[Interview Cake guide to Heaps](https://www.interviewcake.com/concept/python/heap)

## Next Steps

If you haven't already, look at [Binary Search Trees](./binary_search_tree.md) and [Tree Traversals](../algorithms/tree_traversals.md)


