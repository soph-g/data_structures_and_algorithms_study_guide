# Stacks

## Prerequisites

You could use an [Array](./array.md) to build a Stack (or a doubly [Linked List](./linked_lists/.md)), so it's good to be confident using both of these data structures.

[Queues](./queues.md) are similar to Stacks, so it's a good idea to learn these two types together.

## Introduction

Just like a Queue, a Stack is an ordered list of elements, with limited functionality:

- `push` - adds an item to the stack
- `pop` - pops an element off the stack, using Last In First Out ordering
- `peek` - Returns the item at the top of the stack, without popping it off
- `isEmpty` - returns `true` when the stack is empty

An Array is a good option for a simple stack, because adding to the end of an array and popping the last element off an array can both be done in `O(1)` time.

If, however, you might need to delete items from the middle of the Stack, then a doubly Linked List might be a better approach.

## Study Areas

- [ ] Explain how Last In First Out (LIFO) ordering will result in elements being popped off the stack
- [ ] Build a queue, using an Array or Linked List. You should be able to `push`, `pop` and `peek` in `O(1)` time.

## Practice Problems

- [ ] (Implement Stack Using Queue)[https://leetcode.com/problems/implement-stack-using-queue]
- [ ] (Implement Queue Using Stacks)[https://leetcode.com/problems/implement-queue-using-stacks]
- [ ] (Remove Outermost Parenthese)[https://leetcode.com/problems/remove-outermost-parenthese]
- [ ] (Number of Students Unable to Eat Lunch)[https://leetcode.com/problems/number-of-students-unable-to-eat-lunch]
- [ ] (Simplify Path)[https://leetcode.com/problems/simplify-path] 

## Resources

- [Interview Cake article on Stacks](https://www.interviewcake.com/concept/python/stack)

The Cracking the Coding Interview chapter on Stacks & Queues has some great practice problems.

## Next Steps

From this point, [Trees]() _(content coming soon)_ are a good next step.

Or, if you wanted to start learning algorithms, [Binary Search]() _(content coming soon)_ is a good place to start.
