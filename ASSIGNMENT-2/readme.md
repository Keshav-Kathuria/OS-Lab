# Operating Systems – Assignment 2

This repository contains a Python program demonstrating **basic multiprocessing and system process simulation** in an operating system-like environment.

The program creates multiple processes, simulates their execution, and logs the start and end of each process to a log file.

---

## 📌 Task — System Startup Simulation (Multiprocessing)

**File:** `task.py`  

Features:  
- Demonstrates **concurrent execution** using Python’s `multiprocessing` module  
- Launches multiple processes (`Process-1` and `Process-2`)  
- Logs process events to `process_log.txt`  
- Simulates:
  - System Startup
  - Individual process execution
  - System Shutdown  

Shows how operating systems handle **parallel process execution** and **logging**.

---

## How to Run

Run the program using:

`python assignment2.py`

Expected Output (Terminal):  

System Starting...  
System Shutdown.

Log File (`process_log.txt`) Sample Content:  

2025-07-16 12:35:21,005 - Process-1 - Process-1 started  
2025-07-16 12:35:21,006 - Process-2 - Process-2 started  
2025-07-16 12:35:23,007 - Process-1 - Process-1 ended  
2025-07-16 12:35:23,008 - Process-2 - Process-2 ended

---

## Conclusion

- Successfully simulated a system startup with multiple processes.  
- Demonstrated **multiprocessing** and **concurrent execution** in Python.  
- Logging provided a clear trace of process execution and termination.
