# Hi, I'm Gaurav 👋

A Computer Science undergrad specializing in Artificial Intelligence (Class of 2028), driven by a passion for **ultra-low-latency engineering, systems architecture, and Quantitative Finance**. My primary focus is building high-performance, real-time trading systems and optimizing algorithmic efficiency down to the nanosecond. 

Whether it's optimizing time/space complexity in competitive programming or engineering core trading infrastructure, I thrive on squeezing maximum performance out of hardware and software.

### ⚡ Core Competencies & HFT Focus
* **Competitive Programming (C++):** Actively solving advanced Data Structures and Algorithms on **LeetCode** and **Codeforces**. Trained in writing highly optimized, competitive-grade C++ under strict time constraints.
* **Low-Latency Engineering:** Deepening knowledge in C++ memory models, cache-line optimization, lock-free data structures, custom allocators, and zero-allocation data paths.
* **System Architecture:** Designing event-driven backends, market data feed handlers, and real-time execution algorithms.

### 🛠️ The Tech Stack
* **Core Languages:** Modern C++ (C++17/20), Python (for quantitative analysis & prototyping), Java.
* **Systems & Networking:** Linux/POSIX, TCP/UDP sockets, Event loops (epoll), Multithreading.
* **Backend & Databases:** FastAPI, PostgreSQL, MongoDB, SQLite.
* **DevOps & Tooling:** Docker, Git, CMake, Postman.

### 🚀 Cutting-Edge Technologies (Current Research & Learning Path)
To stay ahead in the HFT space, I am actively expanding my knowledge into the extreme edge of hardware and network performance:
* **Kernel Bypass Networking:** Exploring **DPDK** (Data Plane Development Kit) and **RDMA** (Remote Direct Memory Access) to bypass the OS kernel network stack and slash microsecond latencies.
* **Hardware Acceleration:** Studying the fundamentals of **FPGAs** (Field-Programmable Gate Arrays) and SmartNICs for hardware-level market data decoding and order execution.

### 🚧 Currently Functioning Projects
* **Lock-Free Limit Order Book (Matching Engine):** Developing a high-performance C++ matching engine that processes millions of orders per second. Utilizing **Single-Producer Single-Consumer (SPSC) Ring Buffers** and cache-line padding to prevent false sharing and achieve sub-100 nanosecond order processing without OS mutex locks.
* **Zero-Copy NASDAQ ITCH Market Data Feed Handler:** Building a C++ parser to decode raw binary market data directly from the exchange. Engineered with a strict **zero-allocation architecture** (no `new` or `malloc` on the hot path), utilizing `reinterpret_cast` into packed structs to rebuild order book states instantly with zero memory copying.

### 📫 Let's Connect
I am always open to collaborating on high-performance systems, algorithmic trading projects, or discussing C++ internals. 

- **LinkedIn** : [https://www.linkedin.com/in/gaurav-kd-05922b383/]
- **LeetCode** : [https://leetcode.com/u/Gaurav_kd/]
- **CodeFrces** : [https://codeforces.com/profile/gauravkd2015]
- **Email** : [Gauravkd2015@gmail.com]
