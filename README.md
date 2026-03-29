# Hi there, I'm David 👋

## 🎓 About Me

I'm a **Computer Engineering** in my final year, passionate about **embedded systems**, **systems programming**, and **low-level software development**. With hands-on experience in educational settings and multiple university projects, I'm actively seeking opportunities to transition into the software industry.

Currently, I work as a teaching assistant for Digital Electronics 3, where I help students understand microcontroller programming and embedded system design.

## 💼 What I'm Looking For

I'm actively seeking **entry-level positions** or **junior developer roles** in:
- Embedded Systems Development
- Systems Programming
- Firmware Development
- Backend Development
- DevOps/Infrastructure

## 🛠️ Technical Skills

### Programming Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-654FF0?style=for-the-badge&logo=assemblyscript&logoColor=white)

### Learning
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

### Embedded Systems & Hardware
![ARM](https://img.shields.io/badge/ARM%20Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![Microchip](https://img.shields.io/badge/PIC-EE3233?style=for-the-badge&logo=microchip&logoColor=white)
![NXP](https://img.shields.io/badge/NXP%20LPC1769-000000?style=for-the-badge)

### Operating Systems & Platforms
![](https://go-skill-icons.vercel.app/api/icons?i=linux,fedora,windows,ubuntu,mint,manjaro)

### Databases
![](https://go-skill-icons.vercel.app/api/icons?i=mysql,mongodb,sqlite) 

### Tools & Technologies
![](https://go-skill-icons.vercel.app/api/icons?i=git,docker,prometheus,grafana,markdown) 

### Development Environment
![](https://go-skill-icons.vercel.app/api/icons?i=clion,idea) 

### Learning & Community
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![HackerRank](https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white)
![Sololearn](https://img.shields.io/badge/-Sololearn-3a464b?style=for-the-badge&logo=Sololearn&logoColor=white)

### Areas of Expertise
- **Embedded Systems**: Bare-metal programming, CMSIS, peripheral drivers
- **Operating Systems**: Linux internals, process management, file systems
- **Data Structures & Algorithms**: Graph algorithms, routing protocols
- **System Monitoring**: Observability, metrics collection
- **DevOps**: Containerization, monitoring, infrastructure

## 🚀 Featured Projects

### ![](https://go-skill-icons.vercel.app/api/icons?i=c) [LPC17xx CMSIS Driver Enhancement](https://github.com/David-A-T-M/LPC17xx-CMSIS-Driver-Enhancement)

**Embedded Systems | ARM Cortex-M3 | Testing**
<details>
  <summary><b>DETAILS</b></summary>
Complete refactor and enhancement of NXP LPC1769 microcontroller drivers, improving code quality, maintainability, and following modern embedded programming practices.

- ✨ Restructured original NXP drivers for better modularity
- 📚 Enhanced documentation and code readability
- 🎯 Implemented clean API design for peripheral access
- 🔧 Used in teaching materials for Digital Electronics 3
</details>

### ![](https://go-skill-icons.vercel.app/api/icons?i=cpp) [Router Simulator with Dijkstra V2.0](https://github.com/David-A-T-M/RouterSimulator_cpp)
**C++20 | Dijkstra’s Algorithm | STL | Systems Architecture**
<details>
  <summary><b>DETAILS</b></summary>
A robust, event-driven network simulator designed to model packet routing and reassembly in congested topologies. Refactored for high memory efficiency and architectural decoupling.

📊 **Real-time Network Monitoring**
The simulator provides a detailed dashboard of the network state, tracking performance metrics across layers:

<img width="324" height="463" alt="image_2026-02-28_115401283" src="https://github.com/user-attachments/assets/979b1810-bfa8-4e44-aa8c-844652b618a0" />

- ⚡ **Modern C++20 Engine:** Leverages Concepts, Ranges, and Smart Pointers for a memory-safe, type-secure simulation core.
- 🧠 **Dynamic Routing:** Implements a custom Dijkstra-based engine that recalculates optimal paths in real-time based on network load and topology changes.
- 📦 **Packet Reassembly Logic:** Sophisticated handling of multi-packet pages with unique {Source IP, Page ID} identification and timeout management.
- 📊 **Observability:** Features a decoupled architecture currently being extended to support Prometheus metric exporting and real-time Grafana dashboards.
- 🛠️ **Robust Engineering:** Zero-warning build (Clang-Tidy/Cppcheck) with automated CI/CD for style and static analysis.
- 🗺️ **Roadmap & Future Enhancements:** The architecture is designed to be extensible. Current development goals include:
  - [ ] 📈 Full Observability Suite: Integration with Prometheus (Textfile Collector) and Grafana for advanced time-series analysis.
  - [ ] ⚙️ External Configuration: Moving from hardcoded parameters to JSON-based configuration for dynamic simulation setups.
  - [ ] 🧵 Multithreading Engine: Parallelizing router processing logic to handle massive network topologies (1000+ nodes).
  - [ ] 🎨 Interactive UI: Transitioning from CLI to a graphical interface using Dear ImGui or SFML.
</details>

### ![](https://go-skill-icons.vercel.app/api/icons?i=java) [Router Simulator with Dijkstra V1.0](https://github.com/David-A-T-M/RouterSimulator_java)
**Java 21 | Gradle Kotlin DSL | JUnit 5 | Dijkstra**

<details>
  <summary><b>DETAILS</b></summary>
A high-fidelity network simulation engine migrated from C++20 to **Java 21**. This project focuses on **Enterprise Backend Architecture**, implementing robust routing algorithms and automated telemetry collection using modern Java features and SOLID principles.

- 🧠 **The "Systems to Backend" Transition**. This repository represents a strategic evolution from low-level C++ systems programming to a scalable Java-based architecture. Key improvements include:
  - **Type Safety & Generics:** Elimination of manual casting through a decoupled `NetworkNode<T extends Stats>` hierarchy.
  - **Functional Telemetry:** Using Java Streams and Map-Reduce patterns for real-time statistics aggregation.
  - **Immutable Data Carriers:** Extensive use of **Java Records** for thread-safe state snapshots.
- 🛠️ **Tech Stack**
  - **Language:** Java 21 (LTS)
  - **Build System:** Gradle (Kotlin DSL - `build.gradle.kts`)
  - **Testing:** JUnit 5 (Jupiter) & AssertJ
  - **Quality:** Google Java Style Guide via Checkstyle
  - **CI/CD:** GitHub Actions for automated verification
- 🚀 **Key Features**
  - **Dynamic Dijkstra Routing:** Real-time routing table recalculation based on network load and buffer congestion.
  - **Packet Reassembly Logic:** Sophisticated tracking of multi-packet `Page` objects with unique `{Source IP, Page ID}` identification and timeout/quarantine management.
  - **Fluent Builder Pattern:** A specialized `NetworkStats.Builder` for incremental, error-resistant accumulation of global metrics.
- 🧪 **Testing & Reliability.** The project maintains high standards of reliability with a comprehensive **JUnit 5** test suite:
  - **Unit Testing:** Individual logic verification for Dijkstra edge cases (isolated nodes, 1-node networks).
  - **Integration Testing:** Full-cycle simulation tests verifying that `packetsSent` at source equals `packetsReceived` + `packetsDropped` + `packetsTimedOut`.
  - **Property Validation:** Record-level validation using compact constructors to ensure network invariants.
- 🗺️ Backend Roadmap. I am evolving this simulator into a professional Backend showcase:
  - [ ] **Spring Boot REST API:** Expose simulation control and stats via HTTP endpoints.
  - [ ] **Persistence (JPA/Hibernate):** Store simulation history in **PostgreSQL**.
  - [ ] **Observability:** Integration with **Prometheus** and **Grafana** for real-time monitoring.
  - [ ] **Concurrency:** Implementation of **Java 21 Virtual Threads** to scale to 100k+ nodes.
</details>

### ![](https://go-skill-icons.vercel.app/api/icons?i=java) [Petri Net Engine & Visualizer](https://github.com/David-A-T-M/PetriNet_Simulator)
**Java 21 | JavaFX | Jackson | Software Architecture**

<details>
  <summary><b>DETAILS</b></summary>
A high-performance Petri Net simulation engine featuring a decoupled architecture and real-time visualization.

- 🏗️ **Architectural Decoupling.** The system is strictly divided into three specialized domains to ensure maintainability:
  - **Logic Engine:** Pure mathematical representation of the Petri Net (Incidence matrices, firing rules, and marking invariants).
  - **Layout Engine:** Orthogonal (Manhattan) and curved path routing for clear visualization of complex topologies.
  - **Workspace Manager:** A "Master Config" system that allows switching between different models (Producer-Consumer, Dining Philosophers, Resource Allocation) via JSON injection.
- 🚀 **Advanced Java 21 Features**
  - **Domain Modeling with Records:** Extensive use of deeply nested Java Records to handle immutable configuration states (Layouts, Waypoints, and Petri Logic).
  - **Functional Pipelines:** Leveraging Java Streams and Optionals for robust configuration loading and error handling.
  - **Modern JavaFX UI:** Custom rendering engine that uses `PathTransition` and `ParallelTransition` to animate tokens across multi-segment paths.
- 🛠️ **Key Technical Milestones**
  - **Flexible JSON Configuration:** Moving from hardcoded parameters to a fully externalized JSON system, enabling "hot-swapping" of network models.
  - **Concurrency & Events:** Event-driven communication between the simulation relay and the UI layer to ensure smooth animations without blocking the engine's logic.
- 🗺️ **Roadmap & Evolution**
  - [ ] **Observability Suite:** Integration with **Prometheus** and **Grafana** to monitor transition firing rates and place congestion in real-time.
  - [ ] **Persistence Layer:** Implementation of **SQLite** to log simulation history and enable "Time-Travel" debugging/replay.
  - [ ] **Interactive Designer:** Transitioning from JSON-only setups to a Drag & Drop GUI for real-time Petri Net modeling.
</details>

### ![](https://go-skill-icons.vercel.app/api/icons?i=c,linux) [Linux System Monitor](https://github.com/David-A-T-M/Monitoring_project_so1)
**Linux | Prometheus | Grafana | DevOps** *(Refactor in progress)*

<details>
  <summary><b>DETAILS</b></summary>
Real-time system monitoring solution that reads from the Linux `/proc` filesystem and visualizes metrics using modern observability tools.

- 📈 Collects system metrics from /proc filesystem
- 🔍 Integrates Prometheus for metrics storage
- 📊 Creates Grafana dashboards for visualization
- ⚡ Demonstrates understanding of Linux internals and monitoring best practices
</details>

### ![](https://go-skill-icons.vercel.app/api/icons?i=c) [Digital Electronics 3 Workshops](https://github.com/David-A-T-M/DigitalElectronics3_Workshops)
**Educational | ARM**

<details>
  <summary><b>DETAILS</b></summary>
Teaching materials and workshop exercises for microcontroller programming course, designed to help students learn embedded systems development.

- 🎓 Hands-on exercises for LPC1769 microcontroller
- 📝 Comprehensive documentation and learning materials
- 🔨 Practical examples of peripheral usage (GPIO, timers, UART, etc.)
</details>

### ![](https://go-skill-icons.vercel.app/api/icons?i=c,linux) [Custom Linux Shell](https://github.com/David-A-T-M/CustomShell)
**Linux | System Programming** *(Under Development)*

<details>
  <summary><b>DETAILS</b></summary>
Implementation of a custom command-line shell with built-in commands, process management, and piping capabilities.

- 🖥️ Built from scratch in C
- ⚙️ Process creation and management
- 🔀 Pipeline and redirection support
</details>

## 📫 Let's Connect

I'm always interested in discussing embedded systems, low-level programming, or potential opportunities!

- ![](https://go-skill-icons.vercel.app/api/icons?i=linkedin) [LinkedIn](https://www.linkedin.com/in/david-alvin-trujillo-medina-18a265372)
- ![](https://go-skill-icons.vercel.app/api/icons?i=gmail)  [Email](d.trujillo@unc.edu.ar)
- ![](https://go-skill-icons.vercel.app/api/icons?i=android)  +5493517734079

---

⭐️ Feel free to explore my repositories and don't hesitate to reach out!
  


<!--
**David-A-T-M/David-A-T-M** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
