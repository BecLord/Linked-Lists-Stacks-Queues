# Linked Lists, Stacks, and Queues

This project was completed as a project during Semester 1, Year 2 for my Linear Data Structures and Algorithms module.

The project implements linear data structures in Java using fixed-size arrays and a dynamically allocated doubly linked list.

## Project structure

| File | Description |
| --- | --- |
| `List.java` | Interface for the doubly linked list API |
| `DoubleLinkedList.java` | Doubly linked list implementation |
| `Stack.java` | Interface for the stack API |
| `ArrayStack.java` | Stack implemented with a fixed-size array |
| `DynamicStack.java` | Stack implemented with `DoubleLinkedList` |
| `Queue.java` | Interface for the queue API |
| `ArrayQueue.java` | Queue implemented with a fixed-size array |
| `DynamicQueue.java` | Queue implemented with `DoubleLinkedList` |

## Implemented data structures

### Doubly linked list

The list supports operations at both ends:

- `prepend`, `getFirst`, and `deleteFirst`
- `append`, `getLast`, and `deleteLast`
- `empty`

### Stack

The stack follows Last-In, First-Out (LIFO) behavior:

- `push` adds an item
- `pop` removes and returns the top item
- `peek` returns the top item without removing it
- `empty` checks whether the stack is empty

### Queue

The queue follows First-In, First-Out (FIFO) behavior:

- `enqueue` adds an item
- `dequeue` removes and returns the next item
- `next` returns the next item without removing it
- `empty` checks whether the queue is empty

## Compilation and execution

The source files use the `assignment1` package and include example `main` methods.

Compile all source files and run an example from the project directory:

```powershell
javac -d out *.java
java -cp out assignment1.ArrayStack
```

Other example entry points are:

```powershell
java -cp out assignment1.DoubleLinkedList
java -cp out assignment1.DynamicStack
java -cp out assignment1.ArrayQueue
java -cp out assignment1.DynamicQueue
```
