# 🔒 Reader-Writer Problem Simulation (C, POSIX Threads)

This is a C-based simulation of the **Reader-Writer Problem**, demonstrating thread synchronization using **POSIX threads (pthreads)** and **semaphores**. It handles concurrent access to a shared resource by multiple reader and writer threads while maintaining data consistency and tracking access time.

---

## ✅ Features

- 👥 Creates multiple **reader and writer threads**  
- ⏱️ Logs time of **request, entry, and exit** for each thread  
- 🧮 Calculates **average wait time** in the critical section  
- 🔁 Ensures **synchronization** using semaphores (`mutex`, `rwmutex`, `avgmutex`)  
- 📂 Reads thread counts from an external file (`input.txt`)

---

## 🔧 Requirements

- GCC compiler  
- Linux-based system  
- POSIX thread support (`-lpthread`)  
- System call support for syscall 336 (or you may comment it out if unsupported)
