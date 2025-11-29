# 🖥️ Operating Systems Lab – Assignments Repository

This repository contains all **assignments for the Operating Systems Lab** course.  
Each assignment demonstrates key **OS concepts** such as **process management, multiprocessing, scheduling, inter-process communication, and system inspection**.

All assignments are organized in **separate folders** and files for clarity and easy execution.  

---

## 📌 Assignment Overview

### **Assignment 1 — Process Management** ⚙️
**Files:** `task-1.py`, `task-2.py`, `task-3.py`, `task-4.py`, `task-5.py`  

**Description:**  
- Covers process creation, child-parent relationships, executing system commands, zombie and orphan processes, inspecting `/proc`, and process prioritization.  
- Demonstrates Linux process behavior using Python.  
- **Expected output:** child-parent process trees, executed system commands, zombie/orphan states, process details from `/proc`, and execution order based on priority.

---

### **Assignment 2 — System Startup Simulation** 🚀
**Files:** `task.py`, `process_log.txt`  

**Description:**  
- Simulates a basic system startup with multiple processes using Python's `multiprocessing` module.  
- Logs start and end of each process to `process_log.txt`.  
- Demonstrates concurrent process execution and logging.  
- **Terminal output:** "System Starting..." and "System Shutdown." Logs record process execution details.

---

### **Assignment 3 — Inter-Process Communication (IPC)** 🔗
**Files:** `task-1.py`, `task-2.py`, `task-3.py`, `task-4.py`, `task-5.py`  

**Description:**  
- Implements IPC using `os.pipe()` and `os.fork()`.  
- Parent sends a message through the pipe, child receives it.  
- Demonstrates basic process communication.  
- **Note:** Works only on Linux/Unix systems.

---

### **Assignment 4 — Virtual Machine Detection** 🖲️
**Files:** `task-1.py`, `task-2.py`, `task-3.py`, `task-4.py`, `task-5.py`  

**Description:**  
- Checks system information using Linux commands (`uname`, `lscpu`).  
- Detects if the system is running on a virtual machine using `systemd-detect-virt`.  
- Prints either **“Real hardware”** or the type of virtual environment detected.

---

### **Assignment 5 — CPU Scheduling Algorithms** ⏱️
**Files:** `task-1.py`, `task-2.py`, `task-3.py`, `task-4.py`, `task-5.py`  

**Description:**  
- Implements **FCFS, SJF, Round Robin, and Priority Scheduling**.  
- Displays **Burst Time, Waiting Time, and Turnaround Time** for each algorithm.  
- Demonstrates how different scheduling strategies affect process execution.

---

## 🗂️ Repository Structure

- **OS-LAB/**  
  - **ASSIGNMENT-1/**  
    - readme.md  
    - task-1.py  
    - task-2.py  
    - task-3.py  
    - task-4.py  
    - task-5.py  
  - **ASSIGNMENT-2/**  
    - readme.md  
    - task.py  
    - process_log.txt  
  - **ASSIGNMENT-3/**  
    - readme.md  
    - task-1.py  
    - task-2.py  
    - task-3.py  
    - task-4.py  
    - task-5.py  
  - **ASSIGNMENT-4/**  
    - readme.md  
    - task-1.py  
    - task-2.py  
    - task-3.py  
    - task-4.py  
    - task-5.py  
  - **ASSIGNMENT-5/**  
    - readme.md  
    - task-1.py  
    - task-2.py  
    - task-3.py  
    - task-4.py  
    - task-5.py  
  - README.md  

---

## ▶️ How to Run

- Each assignment can be run independently using **Python 3**.  
- Some tasks (e.g., `fork`, `/proc` inspection) require **Linux/Unix systems**.  
- For Assignment 2, check `process_log.txt` for process logs.  
- For CPU scheduling tasks, review terminal output to see scheduling behavior.

---

## ✅ Conclusion

This repository demonstrates essential **Operating System concepts** through practical Python programs:  

- ⚡ **Process creation and management**  
- 🔄 **Concurrent execution with multiprocessing**  
- 🔗 **Inter-process communication (IPC)**  
- 🖥️ **System inspection and monitoring**  
- ⏱️ **CPU scheduling algorithms and priority handling**  

