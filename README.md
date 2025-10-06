# 🧠 Maximum Subarray Algorithms — Performance Comparison

This project implements and benchmarks **four classical algorithms** for solving the **Maximum Subarray Problem**, a famous problem in computer science and algorithm analysis.  

The goal is to find the **contiguous subarray** within a one-dimensional array of numbers that has the **largest sum**.

---

## 🚀 Implemented Algorithms

| Algorithm | Time Complexity | Description |
|------------|----------------|--------------|
| **Brute Force (O(n³))** | Cubic | Checks all possible subarrays using three nested loops. |
| **Improved Brute Force (O(n²))** | Quadratic | Avoids recomputing sums by extending the subarray dynamically. |
| **Divide & Conquer (O(n log n))** | Log-linear | Bentley’s recursive algorithm splitting the array into halves. |
| **Kadane’s Algorithm (O(n))** | Linear | Optimal single-pass solution — tracks current and global maxima. |

---

## 📊 Features

- Benchmarks all algorithms on randomly generated arrays.  
- Reports execution times for different input sizes.  
- Demonstrates the drastic performance improvements between algorithms.  
- Clean, well-documented Python implementation with explanations.  

---

## 📦 Dependencies

Make sure you have the following installed:
```
pip install pandas numpy matplotlib
```

## 🧮 File Structure
```
max-subarray-benchmark/
│
├── procodef.ipynb        # Implementation and benchmarking script
├── README.md             # Project documentation
└── LICENSE               # License (MIT)
```

## 📚 References

- Jon Bentley, “Programming Pearls” — original divide & conquer version.

- Kadane, J. (1984) — optimal O(n) algorithm for the maximum subarray problem.

- CLRS — Introduction to Algorithms, Chapter on Dynamic Programming

## 🧑‍💻 Author

Developed by: [Nima Nadgaran](https://github.com/NimaNadgaran)

Language: Python 3

Course / Context: Algorithm analysis and performance benchmarking.
