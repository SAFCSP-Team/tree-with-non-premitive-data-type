# Tree project

### Objective
The project's main focus is understanding how to build a tree, declare the tree, access tree nodes using pointers, and perform operations on them.

### Problem
Create a tree to store names and print them.

We will create a tree as it's shown in the below image:

<img width="910" alt="Introduction to tree" src="https://github.com/SAFCSP-Team/tree-with-non-premitive-data-type/blob/main/Images/TreeOfStrings.jpg">


### Implementation

Using Java programming language: 

In `Tree` class:

1. Write a function that prints all tree values.
2. Write a function that searches for a specific name in the tree and returns true if it is found, and false otherwise.

In `main` class:   
  
1. Declare a tree and pass the root to it.   
2. Access the root data (name) and print it.   
3. Access and update the root data to be "Anas".   
4. Create root children as shown in the image above.   
5. Print the tree values.   
6. Call the search method to search for "Rashed".   
9. The output should be the same as below:  
    
```java 

Print root value
Ahmed
Print tree values
Anas
Fatema
Rashed
Faisal
Abdullah
Yasser
Salem
Maha
Sami
Jasser
Lena
true

```



```java

import java.util.Stack;

class Node {

    // Data
    String name;
    // Pointers
    Node left;
    Node center;
    Node right;

    // Constructor
    Node(String name) {
        this.name = name;
        this.left = null;
        this.center = null;
        this.right = null;
    }

}

class Tree {

    Node root;

    public Tree(Node root) {
        this.root = root;
    }

    public Tree() {
        root = null;
    }


    // 1 - Write a function that prints all tree values
    /* Your code here  */ 

   
    // 2 - Write function that search for a pecific name in the tree and returns true if the it's found and return false otherwis 
    /* Your code here  */ 

    

    public static void main(String[] args) {
/* 
    3 - Declare Tree
    4 - Access the root data and print it
    5 - Access and update the root data to be (Anas)
    6 - Create root children as the image above shows
    7 - Print tree values
    8 - Search for (Rashed) call the search method
*/
        
        /* Your code here  */ 

    }

}



```
