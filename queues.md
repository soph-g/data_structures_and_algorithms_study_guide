# Queues

## Prerequisites
If you need to implement a queue to solve a problem, you'll normally need to build a [Linked List](./linked_lists.md).

## Introduction

A queue is an ordered list of elements, with a limited functionality. You can do the following actions on a queue:

- enqueue -> add a new element to the end of the queue
- dequeue -> dequeue an element using First In First Out ordering
- peek -> see the value at the top of the queue (i.e. the next element that will be dequeued)
- length / size -> check how long the queue is

As mentioned above, a Linked List is often a good option for implementing a queue. This is because you can add elements to the tail of the linked list, and remove elements from it's head - all in `O(1)` time.

You could also use an [Array](./arrays.md) to implement a queue, using a pointer to keep track of the head of the list. However, if you need to remove elements from the middle of the list then a linked list is usually a better option. 

## Study Areas

- [ ] Explain how First In First Out (FIFO) ordering will result in elements being dequeued.
- [ ] Build a queue, using a Linked List. You should be able to enqueue, dequeue and peek in `O(1)` time
- [ ] Add the ability to delete from the queue, while maintaining queue order. _Hint, this will be hard in a Singly Linked List!_
- [ ] Build a queue, using an Array. You should be able to enqueue, dequeue and peek in `O(1)` time. 

## Practice Problems

- [ ] [Time needed to buy tickets](https://leetcode.com/problems/time-needed-to-buy-tickets)

The next problems are all 'Medium' - for more 'Easy' practice skip to [Stacks]() _content coming soon_
- [ ] [Reveal cards in increasing order](https://leetcode.com/problems/reveal-cards-in-increasing-order)
- [ ] [Find the winner of the circular game](https://leetcode.com/problems/find-the-winner-of-the-circular-game)
- [ ] [LRU Cache](https://leetcode.com/problems/lru-cache)

## Resources

- [Interview Cake article on Queues](https://www.interviewcake.com/concept/python/queue);

Cracking the Coding Interview has a nice chapter on Stacks & Queues that has lots of good practice questions.

## Next Steps

A Stack _(content coming soon)_ is similar to a Queue, but instead of FIFO ordering it uses Last In First Out ordering.

Queues can be useful when traversing Trees _(content coming soon)_ or Graphs _(content coming soon)_
