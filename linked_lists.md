# Linked Lists

## Prerequisites

I would recommend understanding both [Arrays](./arrays.md) and [Hash Tables](./hash_tables.md) so you can better understand the differences between the three data structures.

## Introduction

[Arrays](./arrays.md) and [Hash Tables](./hash_tables.md) are data structures you are probably used to working with, but a Linked List is not usually provided as a built-in type.

A linked list is a series of nodes that has been chained together, with each node storing:

1. The value of the node, and
2. A pointer to the next node in the list.

To navigate a Linked List you start from the first node (the **head**), and use a loop to continually access the next node, until you either find the value you are looking for, or the end (the **tail**) of the list.

Linked Lists are not useful if you need to access a specific value in `O(1)` time, but unlike arrays they are extremely performant when adding new values at the start, middle or end of the list. Adding an element to any position in a linked list always takes `O(1)` time, if you access to the node that will point to the new node.

Linked list questions usually involve navigating a Linked List, and changing data within in - both adding and removing nodes. 

## Study Areas

- [ ] Understand how nodes are chained together to form a Linked List
- [ ] Explain what is meant by the `head` of the list, and how this is used to navigate the list
- [ ] Explain what is meant by the `tail` of the list
- [ ] Build your own implementation of a Linked List:
     - [ ] It should be possible to create a new Node that stores a 'value', and add this to the Linked List.
     - [ ] By default, the implementation should add to the `tail` of the linked list, but practice adding nodes to the start and middle of the list.
- [ ] Practice building a list, using your implementation, and then navigating it using a single pointer to find a value.  
- [ ] Explain the difference between a singly and doubly linked list
- [ ] Turn your linked list implementation into a doubly linked list
- [ ] Know the time and space complexity of the following value operations: add, delete, find

## Practice Questions

These problems get progressively harder. As always, don't spend more than 30 minutes trying to solve a problem before switching to learning mode and checking the solution.

- [ ] [Convert Binary Number in a Linked List to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer)
- [ ] [Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list)
- [ ] [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list) Definitely check the solution to this problem if you are still stuck after 30 mins.
- [ ] [Insert Greatest Common Divisors in Linked List](https://leetcode.com/problems/insert-greatest-common-divisors-in-linked-list)
- [ ] [Merge Nodes in Between Zeros](https://leetcode.com/problems/merge-nodes-in-between-zeros)

## Resources

- [Interview Cake article on Linked Lists](https://www.interviewcake.com/concept/python/linked-list)

## Next Steps

One common usecase of a Linked List is a [Queue](./queues.md), making it a good next step _(content coming soon)_

