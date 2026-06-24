# Quick Sort in Java

A simple Java implementation of the **Quick Sort** algorithm using recursion and the **last element as the pivot**.

## 📌 Overview

Quick Sort is a highly efficient **Divide and Conquer** sorting algorithm. It works by selecting a pivot element, partitioning the array around the pivot, and recursively sorting the subarrays.

## 🚀 Features

* Implemented in Java
* Uses recursion
* In-place sorting (requires no extra array)
* Efficient for large datasets
* Demonstrates partitioning using the last element as the pivot

## 📂 File Structure

```text
Quick-Sort/
│
├── QuickSort.java
└── README.md
```

## ⚙️ Algorithm

1. Choose the last element as the pivot.
2. Partition the array so that:

   * Elements smaller than the pivot are placed on the left.
   * Elements greater than the pivot are placed on the right.
3. Place the pivot in its correct sorted position.
4. Recursively apply the same process to the left and right subarrays.

## 💻 Example

### Input

```java
int arr[] = {7, 8, 9, 1, 2};
```

### Output

```text
1 2 7 8 9
```

## 📊 Time Complexity

| Case         | Complexity |
| ------------ | ---------- |
| Best Case    | O(n log n) |
| Average Case | O(n log n) |
| Worst Case   | O(n²)      |

## 📈 Space Complexity

```text
O(log n)
```

(Recursive call stack in the average case)

## ▶️ How to Run

### Compile

```bash
javac QuickSort.java
```

### Execute

```bash
java QuickSort
```

## 📝 Sample Output

```text
1 2 7 8 9
```

## 📚 Learning Objective

This project demonstrates:

* Divide and Conquer strategy
* Recursion in Java
* Array partitioning
* Sorting algorithms and complexity analysis

## 🤝 Contribution

Feel free to fork this repository, improve the implementation, and submit pull requests.

## 📄 License

This project is open source and available under the MIT License.
