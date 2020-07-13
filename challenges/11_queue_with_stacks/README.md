# Queue with Stacks
Implementation of a pseudo-queue class that uses two stack objects internally.

## Challenge
#### Features
Create a brand new __`PseudoQueue`__ class. *Do not use an existing Queue.* Instead, this PseudoQueue class will implement our standard queue interface (the two methods listed below), but will internally only utilize 2 Stack objects. Ensure that you create your class with the following methods:

__`enqueue(value)`__ which inserts value into the PseudoQueue, using a first-in, first-out approach. <br>
__`dequeue()`__ which extracts a value from the PseudoQueue, using a first-in, first-out approach. <br>
The __`Stack`__ instances have only __push__, __pop__, and __peek__ methods. You should use your own Stack implementation. Instantiate these Stack objects in your PseudoQueue constructor.

## Approach & Efficiency
Both Stack and Queue were implemented using a singly linked list methodology. <br>
__Big O space__ for PseudoQueue will be __O(n)__ and <br>
__Big O time__ for PseudoQueue will be __O(n)__.

## API
This implementation has access to the Node class and all the properties of the Linked List and Stack classes.

## Solution
My code is [here.](./queue_with_stacks.py)

## Code Challenge 11 whiteboards:
#### Queue with Stacks - 
![CC-11 Queue-with-Stacks -1](./assets/queue_with_stacks_WB-1.png)

![CC-11 Queue-with-Stacks -2](./assets/queue_with_stacks_WB-2.png)

![CC-11 Queue-with-Stacks -3](./assets/queue_with_stacks_WB-3.png)

![CC-11 Queue-with-Stacks -4](./assets/queue_with_stacks_WB-4.png)

![CC-11 Queue-with-Stacks -5](./assets/queue_with_stacks_WB-5.png)

![CC-11 Queue-with-Stacks -6](./assets/queue_with_stacks_WB-6.png)



## Task Checklist: <br>
- [ ] Top-level README “Table of Contents” is updated <br>
- [ ] Feature tasks for this challenge are completed <br>
- [ ] Unit tests written and passing <br>
    - [ ] “Happy Path” - Expected outcome <br>
    - [ ] Expected failure <br>
    - [X] Edge Case (if applicable/obvious) <br>
- [X] README for this challenge is complete <br>
    - [X] Summary, Description, Approach & Efficiency, Solution <br>
    - [X] Link to code <br>
    - [X] Pictures of whiteboards <br>
