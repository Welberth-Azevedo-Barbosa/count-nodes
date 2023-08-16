# count-nodes
Solution for "Count complete tree nodes"

# Count Complete Binary Tree Nodes

This repository contains a Python solution to count the number of nodes in a complete binary tree. The code is implemented using the TreeNode class and a Solution class.

# Description

A complete binary tree is a binary tree in which every level, except possibly the last, is completely filled, and all nodes are as far left as possible. Given a complete binary tree, the task is to count the total number of nodes in the tree efficiently.

The provided code defines a TreeNode class that represents a node in a binary tree. Each node has a value (val), a left child node (left), and a right child node (right). The Solution class contains a method called countNodes which calculates the total number of nodes in a given complete binary tree.

The solution works by utilizing the properties of complete binary trees. It first calculates the depth of the left and right subtrees. If the depth of the left subtree is equal to the depth of the right subtree, it means the left subtree is a perfect binary tree, and its total number of nodes can be calculated using the formula 2**(depth + 1) - 1. Otherwise, the tree is divided into two parts: the left subtree and the right subtree. The solution recursively counts the nodes in both subtrees and adds 1 for the root node.
