### Hi, I'm Jude! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="Waving Hand" width="35" height="35" />

I am a **Software Engineer** and **Computer Science student** at Toronto Metropolitan University. I am a versatile developer who thrives at the intersection of high-level application architecture and low-level system performance. My expertise spans the entire **Full-Stack** spectrum—from crafting responsive mobile interfaces to engineering high-performance hardware-accelerated engines from scratch.



---
### 📊 GitHub Activity & Statistics
<div align="center">
  <a href="https://github.com/pranesh-2005/github-readme-stats-fast"><img src="https://github-readme-stats-fast.vercel.app/api?username=juderozario08&show_icons=true&theme=tokyonight"/></a>
</div>
<div align="center">
  <a href="https://github.com/pranesh-2005/github-readme-stats-fast"><img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=juderozario08&show_icons=true&theme=tokyonight&hide=css,shell,makefile&layout=compact"/></a>
</div>

---
### 🛠️ Technical Toolkit
<p align="center" style="display: flex; flex-direction: column;">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,cpp,rust,go,py,java,cs,js,ts,tailwind,lua,mongodb,react,dotnet,bash,linux,apple,windows,azure,git" />
  </a>
</p>

---

### 🚀 Current Deep Dive: Custom Editor Engine
I am currently engineering a **cross-platform rendering engine and text editor from scratch** using **C++** and **SDL2**. This project is an exploration of manual memory management and high-performance systems architecture:

* **Engine Core:** Building a hardware-accelerated rendering engine from the ground up, managing raw input loops and custom font rasterization with SDL2.
* **Piece Table Implementation:** Managing document state with a Piece Table data structure to ensure $O(1)$ edit operations and efficient undo/redo systems, regardless of file size.
* **Platform Integration:** Implementing real-time file system monitoring using **Kqueue** (macOS/Darwin) and **Inotify** (Linux).
* **Modal Editing:** Designing a Vim-inspired modal editing system and integrating a custom LSP client for intelligent code assistance.

---

### 👾 Featured Projects

#### ⌨️ Blip - Production-Grade Text Editor
* **Language:** C++, SDL2, CMake
* Built a modular, immediate-mode GUI text editor from scratch, enforcing strict separation of concerns across the text rendering pipeline, platform-agnostic event routing system, and OS-specific abstraction layers to enable independent development.
* Designed and implemented a custom Piece Table data structure achieving O(1) amortized text insertion and deletion across arbitrarily large buffers, with a fully correct undo/redo stack that cleanly handles interleaved edits, cursor state, and memory reclamation.
* Engineered a high-efficiency, near 0% idle CPU event loop backed by a custom cross-platform filesystem watcher, enabling instant hot-reloading of editor configuration at runtime without process restarts.
* Built a cross-platform font management engine integrating Fontconfig (Linux) and CoreText (macOS) via direct low-level C API bindings for dynamic font discovery and rendering.
* Actively integrating Tree-sitter to construct and traverse Abstract Syntax Trees (ASTs) in real time, enabling precise, language-aware semantic syntax highlighting.

#### 📱 Radius - Cross-Platform Mobile App
* **Language:** React Native, Go, PostgreSQL
* Architecting a cross-platform inventory management system utilizing a React Native frontend and a high-concurrency Go (Gin) backend API to handle rapid, real-time stock queries.
* Designing a custom, zero-dependency authentication pipeline implementing Bcrypt password hashing and JWT-based role-based access control (RBAC) to securely manage retail associate and manager permissions.
* Establishing a serverless CI/CD deployment pipeline utilizing Render for the Go backend and Neon.tech for the PostgreSQL database to ensure scalable, cloud-native hosting.
* Currently Integrating: Native camera APIs and Google MLKit to achieve real-time, on-device barcode scanning, replacing traditional, expensive RF hardware.

#### 🧮 Truth Table Simulator
* **Language:** Go
* Developed a Boolean algebra simulator using AST construction and equivalence-checking algorithms to process complex expressions and automatically generate truth tables from user input.

#### 🦀 Boggle Solver
* **Language:** Rust
* Implemented a high-performance Boggle solver in Rust using Depth-First Search (DFS) with optimized hash-map lookups for memory-safe, fast grid traversal across all valid word paths.

#### 📝 JSON Parser
* **Language:** Go
* Built a custom JSON parser using recursion and stacks to convert raw JSON strings into strongly typed Go structures (maps, structs, interfaces), with robust validation and precise error handling.

#### 📅 Automated Scheduling Pipeline
* **Language:** Python
* Built an automated scheduling pipeline in Python that parsed unstructured data into validated Google Calendar API events, implementing systematic data validation for accuracy.


---

### 💼 Experience & Leadership
* **Solutions Developer @ PHRI:** Focused on production stability and system-level verification, resolving 15+ critical bugs and leading the migration of legacy apps to modern UI frameworks.
* **Lead Programmer @ Neil McNeil Robotics:** Engineered autonomous navigation systems and sensor integration for competitive robotics.
* **VP Finance @ PACS:** Directed financial planning and budgeting for the Practical Applications of Computer Science student organization.

---

### 📫 Connect with me!
* **LinkedIn:** [linkedin.com/in/jude-a-rozario](https://www.linkedin.com/in/jude-a-rozario)
* **Email:** [juderzro08@gmail.com](mailto:juderzro08@gmail.com)
* **Portfolio:** [juderozario08.github.io](https://github.com/juderozario08)
