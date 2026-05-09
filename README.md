# Inventory Reorder System

## Overview

The Inventory Reorder System is a C++ console-based application developed to manage and organize product inventory efficiently. The project helps in tracking stock availability, identifying low-stock products, generating reorder lists, sorting products, and searching products quickly using different Data Structures and Algorithms concepts.

The system stores product information such as Product ID, Product Name, Category, Stock Quantity, Reorder Level, and Price. It provides a menu-driven interface for easy interaction and demonstrates the practical implementation of searching and sorting algorithms in a real-world inventory management scenario.

## Features

* Display all available products
* Add new products to the inventory
* Identify low-stock products
* Generate reorder lists automatically
* Sort products by stock quantity
* Sort products by product price
* Search products using Binary Search
* Compare Linear Search and Binary Search performance
* Display products category-wise
* User-friendly menu-driven interface

## Technologies Used

* C++
* STL Vector
* Chrono Library
* Object-Based Data Storage using Structures

## Data Structures and Algorithms Used

### Data Structures

* Structure (`struct`)
* Vector (`vector<Product>`)

### Algorithms

* Selection Sort
* Quick Sort
* Binary Search
* Linear Search


## Functionalities

### 1. Product Management

The system stores product details using a `Product` structure that contains:

* Product ID
* Product Name
* Category
* Stock Quantity
* Reorder Level
* Product Price

All products are stored dynamically using vectors.

### 2. Add Product

Users can add new products by entering product details such as ID, name, category, stock quantity, reorder level, and price.


### 3. Display Products

The system displays all products in a properly formatted table showing complete inventory details.

### 4. Low Stock Detection

Products whose stock quantity is less than or equal to the reorder level are identified as low-stock products.

### 5. Sorting Operations

* **Selection Sort** is used to sort products based on stock quantity.
* **Quick Sort** is used to sort products according to price.

### 6. Searching Operations

The system searches products using **Binary Search** after sorting products by Product ID, making searching faster and more efficient.

### 7. Search Benchmarking

The project compares the execution time of:

* Linear Search
* Binary Search

The comparison is done using the C++ Chrono library to analyze search performance.

### 8. Category-wise Display

Users can display products according to categories such as:

* Electronics
* Stationery
* Furniture
* Utility

## How to Run the Project

### Compile the Program

```bash id="66pmdv"
g++ main.cpp -o inventory
```

### Run the Program

```bash id="qy78j7"
./inventory
```

## Learning Outcomes

This project helps in understanding:

* Inventory management logic
* Practical implementation of searching and sorting algorithms
* Time complexity comparison
* Use of vectors and structures in C++
* Menu-driven programming
