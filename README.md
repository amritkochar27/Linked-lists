# Linked-lists

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below image:

image

Representation of Linked List

Let's see how each node of the linked list is represented. Each node consists:

a. A data item

b. An address of another node

We wrap both the data item and the next node reference in a struct as:

struct node

{

int data;

struct node *next;

};

Linked List Utility

Lists are one of the most popular and efficient data structures, with implementation in every programming language like C, C++, Python, Java, and C#.

Apart from that, linked lists are a great way to learn how pointers work. By practicing how to manipulate linked lists, you can prepare yourself to learn more advanced data structures like graphs and trees.

Linked List Applications:

Dynamic memory allocation

Implemented in stack and queue

In undo functionality of softwares

Hash tables, Graphs

Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
