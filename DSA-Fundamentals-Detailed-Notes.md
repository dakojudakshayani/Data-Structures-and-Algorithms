# Data Structures and Algorithms (DSA) – Fundamentals

**Level:** Beginner  
**Purpose:** Learning, revision, placements and technical interviews  
**Topics Covered:** 18

---

# Table of Contents

1. Data
2. Data Types
3. Data Structure
4. Algorithm
5. Types of Data Structures
6. Primitive and Non-Primitive Data Structures
7. Linear and Non-Linear Data Structures
8. Static and Dynamic Data Structures
9. Data Structure Operations
10. Abstract Data Type (ADT)
11. Characteristics of an Algorithm
12. Time Complexity
13. Space Complexity
14. Asymptotic Notations
15. Best, Average and Worst Cases
16. Memory Management Basics
17. Applications of Data Structures
18. Choosing the Right Data Structure

---

# 1. Data

### Definition
Data refers to raw facts and figures that can be processed to produce meaningful information.

### Explanation
Data can be numbers, names, symbols, characters or measurements.

### Examples
- Student name: Rahul
- Student marks: 85
- Age: 21
- Temperature: 30°C

### Real-World Example
A college collects student names and marks. After processing the marks, it generates a result report.

### Key Points
- Data is the basic input for processing.
- Data can be raw or organized.
- Processed data becomes meaningful information.

### Remember
**Data → Processing → Information**

---

# 2. Data Types

### Definition
A data type specifies the kind of value that a variable can store and the operations that can be performed on it.

### Types of Data Types

**1. Primitive Data Types**

These represent basic, individual values.

Examples:
- Integer – 25
- Float – 10.5
- Character – 'A'
- Boolean – True or False

**2. Non-Primitive Data Types**

These represent more complex data, collections or structures.

Examples:
- Array
- String
- Linked List
- Tree

*Note: Classifications can differ between programming languages. For example, strings are primitive in some languages and objects in others.*

### Real-World Example
- Age = 21 → Integer
- Percentage = 85.5 → Float
- Grade = 'A' → Character
- Is_Passed = True → Boolean

### Key Points
- Data type describes the kind of value.
- It determines how a value is represented and used.
- Different languages support different data types.

### Remember
**Data Type = What kind of value is stored?**

---

# 3. Data Structure

### Definition
A data structure is a way of organizing and storing data so that it can be accessed and modified efficiently.

### Explanation
When a program handles large amounts of data, we need a proper way to organize it.

Data structures help us perform operations such as:
- Insertion
- Deletion
- Searching
- Sorting
- Accessing

### Examples
- Array – Stores elements in indexed positions.
- Linked List – Stores connected nodes.
- Stack – Follows LIFO.
- Queue – Follows FIFO.
- Tree – Stores hierarchical data.
- Graph – Represents relationships.

### Real-World Example
A music playlist can use a linked-list-like structure to connect songs.

### Key Points
- Organizes data.
- Makes operations easier.
- Helps improve program efficiency.

### Remember
**Data Structure = How is data organized?**

---

# 4. Algorithm

### Definition
An algorithm is a finite sequence of clear, step-by-step instructions used to solve a problem.

### Explanation
An algorithm describes the logic or procedure for solving a problem.

### Example: Add Two Numbers

1. Start.
2. Read two numbers A and B.
3. Calculate A + B.
4. Display the result.
5. Stop.

**Sample:**

A = 10  
B = 20  
Result = 30

### Real-World Example
Making tea:
1. Boil water.
2. Add tea powder.
3. Add milk and sugar.
4. Boil the mixture.
5. Serve tea.

### Key Points
- An algorithm must have clear steps.
- It should terminate after a finite number of steps.
- It solves a particular problem.

### Remember
**Algorithm = Step-by-step problem-solving procedure.**

---

# 5. Types of Data Structures

### Definition
Data structures are classified into different categories based on the type and organization of data.

### Main Types

**1. Primitive Data Structures**

Basic data representations.

Examples:
- Integer
- Float
- Character
- Boolean

**2. Non-Primitive Data Structures**

More complex structures used to organize collections of data.

They are classified into:

- Linear Data Structures
- Non-Linear Data Structures

### Classification Diagram

```text
             Data Structures
                    |
          ---------------------
          |                   |
       Primitive          Non-Primitive
                              |
                    ---------------------
                    |                   |
                  Linear            Non-Linear
                    |                   |
               Array               Tree
               Linked List         Graph
               Stack               Heap
               Queue               Trie
```

### Remember
**Data Structures → Primitive + Non-Primitive → Linear + Non-Linear**

---

# 6. Primitive and Non-Primitive Data Structures

### 1. Primitive Data Structures

**Definition:** Primitive data structures represent basic, individual data values.

Examples:
- Integer
- Float
- Character
- Boolean

**Example:**

Age = 21

Here, an integer represents the age value.

### 2. Non-Primitive Data Structures

**Definition:** Non-primitive data structures organize collections of data or more complex relationships.

Examples:
- Array
- Linked List
- Stack
- Queue
- Tree
- Graph

**Example:**

Student marks = [80, 85, 90, 95]

An array stores multiple marks together.

### Difference

| Primitive | Non-Primitive |
|---|---|
| Basic values | Complex data organization |
| Usually represents one value | Can represent multiple values |
| int, float, char | Array, Stack, Tree |

### Remember
- Primitive → Basic value.
- Non-Primitive → Collection or complex organization.

---

# 7. Linear and Non-Linear Data Structures

### 1. Linear Data Structure

**Definition:** A linear data structure arranges elements sequentially, one after another.

Examples:
- Array
- Linked List
- Stack
- Queue
- Deque

**Example:**

```text
10 → 20 → 30 → 40
```

Each element follows a sequence.

### 2. Non-Linear Data Structure

**Definition:** A non-linear data structure organizes elements hierarchically or through interconnected relationships.

Examples:
- Tree
- Graph
- Heap
- Trie

**Example: Tree**

```text
          A
        /   \
       B     C
      / \
     D   E
```

### Difference

| Linear | Non-Linear |
|---|---|
| Sequential arrangement | Hierarchical or interconnected arrangement |
| Usually follows a sequence | Can have multiple relationships |
| Array, Stack, Queue | Tree, Graph, Heap |

### Real-World Examples
- Linear → People standing in a queue.
- Non-Linear → Folder hierarchy in a computer.

### Remember
**Linear = Sequential.**  
**Non-Linear = Hierarchical or interconnected.**

---

# 8. Static and Dynamic Data Structures

### 1. Static Data Structure

**Definition:** A static data structure has a fixed size determined during allocation.

**Example:** A fixed-size array.

```text
Array size = 5

[10, 20, 30, 40, 50]
```

The allocated capacity is fixed.

### 2. Dynamic Data Structure

**Definition:** A dynamic data structure can grow or shrink during program execution.

**Examples:**
- Linked List
- Dynamic Array

### Difference

| Static | Dynamic |
|---|---|
| Fixed allocated size | Can grow or shrink |
| Capacity is predetermined | Capacity can change |
| Fixed-size array | Linked List, Dynamic Array |

### Real-World Example
- Static → A classroom with a fixed number of seats.
- Dynamic → An online group where members can join or leave.

### Remember
**Static = Fixed size.**  
**Dynamic = Flexible size.**

---

# 9. Data Structure Operations

### Definition
Data structure operations are actions performed on stored data to manage and manipulate it.

### Important Operations

**1. Insertion**

Adding a new element.

Example:

```text
Before: [10, 20, 30]
After:  [10, 20, 30, 40]
```

**2. Deletion**

Removing an existing element.

Example:

```text
Before: [10, 20, 30]
After:  [10, 30]
```

**3. Searching**

Finding a particular element.

Example: Find 20 in [10, 20, 30].

**4. Traversal**

Visiting each element in a data structure.

Example: Visiting 10, 20 and 30 one by one.

**5. Sorting**

Arranging elements in a particular order.

Example:

```text
Before: [30, 10, 20]
After:  [10, 20, 30]
```

**6. Updating**

Changing an existing element.

Example:

```text
Before: [10, 20, 30]
After:  [10, 25, 30]
```

**7. Accessing**

Retrieving an element from a data structure.

Example: Access the second element of [10, 20, 30] → 20.

### Remember
**I D S T S U A**

Insertion, Deletion, Searching, Traversal, Sorting, Updating, Accessing.

---

# 10. Abstract Data Type (ADT)

### Definition
An Abstract Data Type (ADT) defines the data and operations that can be performed without specifying how they are implemented.

### Explanation
ADT describes what operations are available, not how those operations work internally.

### Example: Stack ADT

A stack follows LIFO (Last In, First Out).

Important operations:

- Push – Add an element.
- Pop – Remove the top element.
- Peek – View the top element.
- IsEmpty – Check whether the stack is empty.

### Real-World Example
A stack of plates:

- Add a plate to the top → Push.
- Remove the top plate → Pop.
- Look at the top plate → Peek.

### Key Points
- ADT focuses on behavior.
- It hides implementation details.
- Different implementations can provide the same ADT.

### Remember
**ADT = What operations are performed, not how they are implemented.**

---

# 11. Characteristics of an Algorithm

### Definition
The characteristics of an algorithm are the essential properties that make its instructions understandable and executable.

### Five Important Characteristics

**1. Input**

An algorithm accepts zero or more inputs.

Example: Two numbers A and B.

**2. Output**

An algorithm produces at least one result.

Example: Sum = 30.

**3. Definiteness**

Every step must be clear and unambiguous.

Example: Add A and B is clear.

**4. Finiteness**

An algorithm must terminate after a finite number of steps.

Example: A calculation should eventually finish.

**5. Effectiveness**

Every instruction must be simple and executable.

Example: Adding two numbers is an executable operation.

### Remember
**I O D F E**

Input, Output, Definiteness, Finiteness, Effectiveness.

---

# 12. Time Complexity

### Definition
Time complexity describes how the running time of an algorithm grows as the input size increases.

### Explanation
It helps us understand how efficient an algorithm is for small and large inputs.

Here, `n` represents the input size.

### Common Time Complexities

| Complexity | Name | Example |
|---|---|---|
| O(1) | Constant | Array index access |
| O(log n) | Logarithmic | Binary Search |
| O(n) | Linear | Linear Search |
| O(n log n) | Linearithmic | Merge Sort |
| O(n²) | Quadratic | Bubble Sort |
| O(n³) | Cubic | Some triple nested-loop algorithms |
| O(2ⁿ) | Exponential | Some recursive subset algorithms |
| O(n!) | Factorial | Brute-force permutation generation |

### Simple Explanation

**O(1):** Time does not grow with input size.

Example: Accessing an array element by index.

**O(log n):** The search space reduces by a constant factor.

Example: Binary Search on sorted data.

**O(n):** Work grows proportionally with input size.

Example: Checking every element in an array.

**O(n²):** Work can grow proportionally to the square of input size.

Example: A basic nested-loop comparison algorithm.

### Complexity Order

From generally faster growth to slower growth:

```text
O(1)
  ↓
O(log n)
  ↓
O(n)
  ↓
O(n log n)
  ↓
O(n²)
  ↓
O(n³)
  ↓
O(2ⁿ)
  ↓
O(n!)
```

### Important Note
The complexity describes growth, not the exact number of seconds. Actual execution time also depends on hardware, language and implementation.

### Remember
**Time Complexity = How does the work grow when input size increases?**

---

# 13. Space Complexity

### Definition
Space complexity describes how the memory requirements of an algorithm grow with input size.

### Explanation
An algorithm needs memory to store variables, data structures and other information during execution.

### Examples

**1. O(1) – Constant Auxiliary Space**

Uses a fixed amount of extra memory.

Example: Using two variables to calculate a sum.

**2. O(n) – Linear Auxiliary Space**

Extra memory grows with input size.

Example: Creating another array of n elements.

**3. O(n²) – Quadratic Auxiliary Space**

Extra memory grows with the square of input size.

Example: Creating an n × n matrix.

### Key Points
- Space complexity measures memory requirements.
- It helps evaluate memory efficiency.
- Auxiliary space refers to extra memory used by an algorithm.

### Remember
**Space Complexity = How much memory does the algorithm need?**

---

# 14. Asymptotic Notations

### Definition
Asymptotic notations describe the growth rate of an algorithm as input size becomes large.

### Three Main Types

**1. Big O – O**

Definition: Represents an asymptotic upper bound on growth.

Example:

An algorithm with O(n²) complexity has an upper-bound growth rate proportional to n².

**2. Omega – Ω**

Definition: Represents an asymptotic lower bound on growth.

Example:

An algorithm with Ω(n) has a lower-bound growth rate proportional to n.

**3. Theta – Θ**

Definition: Represents a tight asymptotic bound when upper and lower bounds match.

Example:

An algorithm with Θ(n) grows linearly.

### Difference

| Notation | Meaning |
|---|---|
| Big O – O | Upper bound |
| Omega – Ω | Lower bound |
| Theta – Θ | Tight bound |

### Remember
- O → Upper.
- Ω → Lower.
- Θ → Tight.

*Important: Big O is commonly used to express algorithmic upper-bound growth; it does not automatically mean worst-case unless the case being analyzed is specified.*

---

# 15. Best, Average and Worst Cases

### Definition
Best, average and worst cases describe an algorithm's performance under different input conditions.

### 1. Best Case

Definition: The minimum amount of work needed for an input of a given size.

Example: Linear Search finds the element at the first position.

Complexity: O(1).

### 2. Average Case

Definition: The expected amount of work for typical inputs under an assumed input distribution.

Example: Linear Search finds an element somewhere in the middle on average.

Complexity: O(n).

### 3. Worst Case

Definition: The maximum amount of work required for an input of a given size.

Example: Linear Search finds the element at the last position or does not find it.

Complexity: O(n).

### Example: Linear Search

Array:

```text
[10, 20, 30, 40, 50]
```

Search for 10:
- Best case → First position → O(1).

Search for 30:
- Typical middle position → O(n) average-case growth.

Search for 50:
- Worst case → Last position → O(n).

### Remember
- Best → Minimum work.
- Average → Expected work.
- Worst → Maximum work.

---

# 16. Memory Management Basics

### Definition
Memory management is the process of allocating, using and releasing memory during program execution.

### Important Terms

**1. Memory Allocation**

Reserving memory for data.

Example: Allocating space for an array.

**2. Memory Deallocation**

Releasing memory that is no longer required.

**3. Static Memory Allocation**

Memory size is determined before or during program setup and remains fixed for that allocation.

Example: A fixed-size array in C.

**4. Dynamic Memory Allocation**

Memory is requested during program execution.

Examples:
- `malloc()` in C.
- `new` in C++.
- Dynamic object allocation in Java.

**5. Memory Leak**

Occurs when allocated memory is no longer needed but is not properly released or made available for reuse.

### Real-World Example
Think of memory as a storage room:
- Allocation → Taking a shelf.
- Usage → Keeping items on it.
- Deallocation → Freeing the shelf.
- Memory leak → Keeping an unused shelf occupied.

### Remember
**Memory Management = Allocate + Use + Release memory.**

---

# 17. Applications of Data Structures

### Definition
Data structures are used in software applications to organize, store, retrieve and process data efficiently.

### Applications

| Data Structure | Application | Example |
|---|---|---|
| Array | Indexed data storage | Student marks |
| Linked List | Sequential connected data | Music playlist |
| Stack | LIFO processing | Undo operation |
| Queue | FIFO processing | Printer queue |
| Tree | Hierarchical data | Folder structure |
| Graph | Connected relationships | Social networks |
| Hash Table | Key-value lookup | Dictionary |
| Heap | Priority processing | Task scheduling |
| Trie | Prefix-based searching | Autocomplete |

### Real-World Explanation

**Array:** Stores student marks using indexed positions.

**Linked List:** Connects songs in a playlist.

**Stack:** Stores recent actions for undo functionality.

**Queue:** Manages documents waiting for printing.

**Tree:** Represents folders and subfolders.

**Graph:** Represents people and their connections in a social network.

**Hash Table:** Stores and retrieves information using keys.

**Heap:** Helps process tasks according to priority.

**Trie:** Helps suggest words while typing.

### Remember
Different data structures solve different data organization problems.

---

# 18. Choosing the Right Data Structure

### Definition
Choosing the right data structure means selecting the most suitable structure based on a problem's requirements.

### Factors to Consider

1. **Type of Data:** What information needs to be stored?
2. **Required Operations:** Is insertion, deletion or searching frequent?
3. **Time Complexity:** How quickly should operations execute?
4. **Space Complexity:** How much memory is available?
5. **Data Size:** How much data needs to be stored?
6. **Memory Requirements:** Is fixed or flexible memory needed?

### Examples

| Requirement | Suitable Data Structure |
|---|---|
| Fast index access | Array |
| Frequent insertion/deletion at known positions | Linked List |
| LIFO operations | Stack |
| FIFO operations | Queue |
| Key-value lookup | Hash Table |
| Hierarchical information | Tree |
| Network connections | Graph |
| Priority-based processing | Heap |
| Prefix searching | Trie |

### Real-World Examples

- Browser back history → Stack.
- Customer waiting line → Queue.
- Computer folder hierarchy → Tree.
- Social network connections → Graph.
- Dictionary lookup → Hash Table.

### Key Points
- No single data structure is best for every problem.
- Choose based on operations and requirements.
- Consider both time and memory efficiency.

### Remember
**Right Data Structure = Better Problem-Solving Efficiency.**

---

# Quick Revision – All 18 Topics

| No. | Topic | One-Line Revision |
|---:|---|---|
| 1 | Data | Raw facts and figures. |
| 2 | Data Types | Specify the kind of value stored. |
| 3 | Data Structure | Organizes and stores data. |
| 4 | Algorithm | Step-by-step problem-solving procedure. |
| 5 | Types of Data Structures | Primitive and Non-Primitive. |
| 6 | Primitive and Non-Primitive | Basic values and complex structures. |
| 7 | Linear and Non-Linear | Sequential and interconnected organization. |
| 8 | Static and Dynamic | Fixed size and flexible size. |
| 9 | Operations | Insertion, deletion, searching, traversal, sorting, updating and accessing. |
| 10 | ADT | Defines operations without implementation details. |
| 11 | Algorithm Characteristics | Input, Output, Definiteness, Finiteness and Effectiveness. |
| 12 | Time Complexity | Growth of running time. |
| 13 | Space Complexity | Growth of memory requirements. |
| 14 | Asymptotic Notations | O, Ω and Θ. |
| 15 | Best, Average and Worst | Minimum, expected and maximum work. |
| 16 | Memory Management | Allocate, use and release memory. |
| 17 | Applications | Real-world uses of data structures. |
| 18 | Choosing the Right Structure | Select based on problem requirements. |

---

# Important Differences for Interviews

| Concepts | Main Difference |
|---|---|
| Data vs Information | Raw facts vs processed meaningful data |
| Data Type vs Data Structure | Type of value vs organization of data |
| Algorithm vs Data Structure | Problem-solving steps vs data organization |
| Primitive vs Non-Primitive | Basic values vs complex structures |
| Linear vs Non-Linear | Sequential vs hierarchical/interconnected |
| Static vs Dynamic | Fixed allocated size vs flexible size |
| ADT vs Data Structure | Logical behavior vs implementation |
| Time vs Space Complexity | Running-time growth vs memory growth |
| Big O vs Omega vs Theta | Upper vs lower vs tight bound |

---

# Placement Interview Practice Questions

### Basic Questions

1. What is data?
2. What is a data type?
3. What is a data structure?
4. What is an algorithm?
5. Why do we need data structures?
6. What are the types of data structures?
7. What is a primitive data structure?
8. What is a non-primitive data structure?
9. What is a linear data structure?
10. What is a non-linear data structure?

### Intermediate Questions

11. Differentiate static and dynamic data structures.
12. Explain the basic operations of data structures.
13. What is an Abstract Data Type?
14. What are the characteristics of an algorithm?
15. What is time complexity?
16. What is space complexity?
17. Explain Big O, Omega and Theta.
18. Differentiate best, average and worst cases.
19. What is memory allocation?
20. What is a memory leak?

### Application-Based Questions

21. Which data structure is suitable for browser back history?
22. Which data structure is used in a printer queue?
23. Which data structure represents a folder hierarchy?
24. Which data structure represents social network connections?
25. Which data structure is useful for priority scheduling?
26. Which data structure is useful for autocomplete?
27. Why is choosing the right data structure important?
28. Can the same problem be solved using different data structures?

---

# Self-Assessment Checklist

Before moving to the next chapter, check whether you can:

- [ ] Define all 18 topics.
- [ ] Explain the types of data structures.
- [ ] Differentiate data types and data structures.
- [ ] Explain linear and non-linear structures.
- [ ] Explain static and dynamic structures.
- [ ] Describe all basic data structure operations.
- [ ] Explain ADT with an example.
- [ ] Identify algorithm characteristics.
- [ ] Explain time and space complexity.
- [ ] Differentiate O, Ω and Θ.
- [ ] Explain best, average and worst cases.
- [ ] Describe basic memory management.
- [ ] Give real-world applications.
- [ ] Choose a suitable data structure for a problem.

---

# Final Learning Order

1. Complete DSA Fundamentals – 18 topics.
2. Revise definitions and examples.
3. Complete the theory assessment.
4. Start Arrays.
5. Continue with the remaining data structures.
6. Learn algorithms and problem-solving techniques.
7. Implement DSA in C, C++, Python and Java.

**Learning Method:** Understand → Example → Logic → Practice → Interview Questions → Test.

---

**End of DSA Fundamentals – Chapter 1**

*Keep revising these notes regularly. Understanding the concept is more important than memorizing the definition.*
