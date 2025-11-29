# Operating Systems – Assignment 1

This repository contains Python programs demonstrating **advanced process management** concepts in Linux.  
The tasks cover process creation, execution, zombie/orphan processes, process inspection, and process prioritization.

Each task is implemented in a separate Python file for clarity and ease of execution.

---

## 📌 Task 1 — Process Creation Utility

**File:** `task1`  

Features:  
- Creates **N child processes** using `os.fork()`  
- Each child prints:
  - Its PID
  - Its Parent PID
  - A custom message  
- The parent waits for all children using `os.wait()`  
- Demonstrates basic process creation and parent-child relationships

---

## 📌 Task 2 — Command Execution Using exec()

**File:** `task2`  

Features:  
- Children execute Linux commands (`ls`, `date`, `ps`) using `os.execvp()`  
- Parent waits for all child processes  
- Demonstrates how processes can execute system commands

---

## 📌 Task 3 — Zombie & Orphan Processes

**File:** `task3`  

Features:  
- Creates **zombie processes** by skipping `wait()` in the parent  
- Creates **orphan processes** by exiting the parent before the child  
- Observed using `ps -el | grep defunct`  
- Demonstrates process states and OS behavior

---

## 📌 Task 4 — Inspecting Process Info from /proc

**File:** `task4`  

Features:  
- Takes a PID as input and prints:
  - Process name, state, memory usage from `/proc/[pid]/status`  
  - Executable path from `/proc/[pid]/exe`  
  - Open file descriptors from `/proc/[pid]/fd`  
- Demonstrates inspecting Linux process information programmatically

---

## 📌 Task 5 — Process Prioritization

**File:** `task5`  

Features:  
- Creates multiple CPU-intensive child processes  
- Assigns different `nice()` values to observe scheduler impact  
- Logs execution order to show effect of process priority  
- Demonstrates CPU scheduling behavior in practice

---

## How to Run

Run any task using Python 3 on a Linux system:

`python taskX.py`  (replace `taskX.py` with the respective file name)

Expected Output (Terminal):  
- Child-parent process tree  
- Executed system commands from child processes  
- Verified zombie/orphan states using `ps`  
- Process details from `/proc`  
- Execution order affected by process priority

---

## Conclusion

- Successfully demonstrated various **process management concepts** in Linux using Python  
- Showed **process creation, execution, state observation, inspection, and prioritization**  
- Separate files for each task make the implementation clear, testable, and organized
