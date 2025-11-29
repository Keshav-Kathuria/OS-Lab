# Operating Systems – Assignment 3

This repository contains 5 Python programs implementing different Operating System concepts.  
Each task is stored in a separate Python file for clarity and easy execution.

---

## 📌 Task 1 — CPU Scheduling (Priority + Round Robin)

**File:** `task1_cpu_scheduling.py`

This program implements:
- Priority Scheduling (Non-Preemptive)
- Round Robin Scheduling with a time quantum

It displays:
- Gantt Chart order (execution sequence)
- Waiting Time (WT)
- Turnaround Time (TAT)
- Average WT and TAT

---

## 📌 Task 2 — Sequential File Allocation

**File:** `task2_sequential_file_allocation.py`

Simulates:
- Sequential / Contiguous allocation of files into disk blocks
- Checks if all required blocks are free
- Allocates or rejects based on availability

---

## 📌 Task 3 — Indexed File Allocation

**File:** `task3_indexed_file_allocation.py`

Features:
- User selects an index block
- User provides the data block list
- Program validates:
  - Block availability
  - Correct count of data blocks  
- On success: Allocates index block → data blocks

---

## 📌 Task 4 — Memory Allocation (First-Fit, Best-Fit, Worst-Fit)

**File:** `task4_memory_allocation.py`

Implements 3 classic memory allocation strategies:
- **First Fit** → First partition large enough
- **Best Fit** → Smallest partition that fits
- **Worst Fit** → Largest partition available

Shows allocation results for each process.

---

## 📌 Task 5 — MFT & MVT Memory Management

**File:** `task5_mft_mvt.py`

### MFT (Multiprogramming with Fixed Tasks)
- Memory is divided into fixed partitions
- A process is allocated only if its size ≤ partition size

### MVT (Multiprogramming with Variable Tasks)
- Memory allocated dynamically
- Reduces internal fragmentation
- Allocation continues until memory is exhausted

---

## 🚀 How to Run

Run any task using the format:

```
python filename.py
```

Example:

```
python task1_cpu_scheduling.py
```
