# Almost Lucky Number Checker (C++)

## 🧩 Problem Description
This program determines whether a given integer $n$ is an "almost lucky" number. A number is considered almost lucky if it is evenly divisible by any core lucky number (numbers made up strictly of the digits 4 and 7, such as 4, 7, 44, 47, etc.).

## 🚀 Optimization & Performance
* **Fast I/O:** Utilizes `ios_base::sync_with_stdio(false); cin.tie(nullptr);` to untie C++ streams from C streams, significantly reducing input/output execution time.
* **Pre-computed Array:** Instead of generating lucky numbers dynamically at runtime, the core lucky numbers up to 1000 are pre-calculated into a fixed array `lucky_nums[12]`. This changes the complexity factor to a highly optimized $O(1)$ space and minimal time evaluation.
* **Range-Based Loop:** Implements modern C++ range-based loops for clean, readable syntax.

## 🛠️ How to Compile and Run
Ensure you have a GCC/G++ compiler installed.

```bash
g++ -O3 main.cpp -o checker
./checker
