# BGU-OperatorOperationsSegmentTrees-Java

Spring 2023 Introduction to Data Structures This project contains the practical exercise solution for an Introduction to Data Structures course held in Spring 2023

Representation of Segment Trees: It discusses representing segment trees using arrays, where each array cell represents a node, and navigation within the tree is facilitated by indices.
Implementation Requirements: The text specifies the necessary array size for efficient representation of segment trees based on the input size. It also provides guidelines for implementing the required functionalities in Java.
Analyzer Number Class: This class is required to manipulate the segment trees previously implemented. It should implement the Iterator and Comparator interfaces for efficient traversal and custom sorting based on even/odd parity.
Implementation Variants: Two implementations of the segment tree are required: one using a tree structure and the other using arrays. The provided abstract classes should be extended to implement specific functionalities like querying, updating, and traversal.
Testing: A Tester class is provided to facilitate testing of the implemented functionalities. It's essential to add tests for each public method, covering boundary cases and diverse scenarios.
Submission Instructions: All implemented classes should be submitted according to the provided submission instructions, ensuring completeness and correctness.
In summary, the task involves implementing segment trees in two different ways (using tree structure and arrays), creating an Analyzer Number class to manipulate these trees, and thoroughly testing the implementations. Finally, all files must be submitted as per the submission guidelines.

Segment Tree: This data structure is used for efficient querying and updating of elements in a given range of an array. It's represented either as a binary tree or an array, with each node containing summary information about the segment it represents.
Analyzer Number Class: This class manipulates segment trees and provides a unified interface for accessing various functionalities. It implements the Iterable interface for iteration over a collection of integers and the Comparator interface for custom sorting based on even/odd parity.
Segment Tree By Tree: This abstract class represents a segment tree implementation using a tree structure. Subclasses, such as MaximumSegmentTreeByTree, MinimumSegmentTreeByTree, and SummationSegmentTreeByTree, implement specific functionalities for maximum, minimum, and sum operations, respectively.
Segment Tree By Array: This abstract class represents a segment tree implementation using an array. Similarly, subclasses like MaximumSegmentTreeByArray, MinimumSegmentTreeByArray, and SummationSegmentTreeByArray implement functionalities for maximum, minimum, and sum operations, respectively.
These data structures are crucial for efficiently performing range queries and updates on large datasets, providing a foundation for implementing complex algorithms and applications.
