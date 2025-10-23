# Java Hash Table with Separate Chaining

This project is a Java implementation of a hash table designed to demonstrate and handle hash collisions. It uses the **separate chaining** method, where each slot in the hash table array holds a `DoublyLinkedList` to store all values that hash to the same index.

This was developed as a project for a Data Structures and Algorithms course.

## ✨ Features

**Hash Table:** A `ChainingHashTable` class that manages an array of linked lists.<br>
**Custom Hash Function:** A `getHash` method that computes a hash value for an integer.<br>
**Collision Resolution:** Uses **separate chaining** to store multiple values in the same hash slot.<br>
**Doubly Linked List:** A complete, from-scratch implementation of a `DoublyLinkedList` to hold the "chains" of colliding data.<br>
**Dynamic Filling:** Supports creating an empty table or filling it with an array of data.<br>
**Test Driver:** Includes a `Collisions.java` class to generate random data and demonstrate the hash table in action.<br>

## 📂 Project Structure

`Collisions.java`: The main class with the `main` method, used to test the hash table.<br>
`ChainingHashTable.java`: The core class containing all the hash table logic (`insert`, `fill`, `getHash`).<br>
`IHashTable.java`: The interface defining the hash table's public methods.<br>
`DoublyLinkedList.java`: A custom implementation of a doubly linked list used for the "chains".<br>
`IDoublyLinkedList.java`: The interface for the doubly linked list.<br>
