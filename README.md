# LinkedList
# Java Linked List Implementations

This repository contains Java implementations of:

- Singly Linked List (SLL)
- Doubly Linked List (DLL)

---

## Files

- `SinglyLList.java`: Implementation of a singly linked list with basic operations.
- `DoublyLList.java`: Implementation of a doubly linked list with basic operations.

---

### Operations Implemented

- `insertatbegin(int data)` - Insert a node at the beginning
- `insertatend(int data)` - Insert a node at the end
- `insertatspecificposition(int data, int position)` - Insert a node at a specific position
- `deleteatbeginning()` - Delete the first node
- `deleteatend()` - Delete the last node
- `deleteatspecificposition(int position)` - Delete a node at a specific position
- `display()` - Print the list

### Sample Usage in Main
```java
list.insertatbegin(10);
list.insertatend(100);
list.insertatspecificposition(75, 2);
list.deleteatbeginning();
list.deleteatend();
list.deleteatspecificposition(2);
list.display();
