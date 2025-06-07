# Data_Structures_and_Algorithms_Assignment_1

Description: Implement and use list data structures to build a library for Multi-Layer Perceptron (MLP) neural networks.

## 1. Introduction

This assignment aims to help students solidify and apply their knowledge of list data structures while getting acquainted with the xtensor library for multi-dimensional array manipulation. The ultimate goal is to build a basic library for MLPs.

## 2. Setup and Usage

Instructions on how to set up, compile, and run the program.

### 2.1. Software Requirements

*   C++ compiler supporting C++17 standard (e.g., g++)
*   xtensor library (provided with the assignment files)

### 2.2. Installation Steps

1.  Extract the source code directory.
2.  Ensure you have a C++ compiler and the xtensor library installed.
3.  (Example) Compile using the command line: `g++ -Iinclude -Isrc -std=c++17 main.cpp`

### 2.3. Usage Instructions

After compiling, run the executable. The program will execute sample test cases and print the results to the console.

## 3. Implemented Components

*   **List Data Structures:**
    *   `XArrayList` (array-based list)
    *   `DLinkedList` (doubly linked list)
*   **Basic MLP Library:**
    *   `Dataset`, `TensorDataset`, `DataLoader` classes
    *   Layer classes: `Layer`, `FCLayer`, `ReLU`, `Softmax`

