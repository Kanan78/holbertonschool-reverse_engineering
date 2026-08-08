# Static Analysis & Reverse Engineering

## Overview
This project focuses on the fundamentals of static analysis—the discipline of examining binary files, understanding their structure, reading assembly code, and extracting meaning without executing the program. 

---

## Scenarios & Practical Application
Static analysis plays a critical role in three main scenarios:
* **Malware Analysis:** Safely examining unknown binaries to understand their behavior before execution.
* **Security Auditing:** Verifying program behavior and security controls without relying on source code.
* **CTF Challenges:** Inspecting compiled binaries to locate hidden flags and analyze underlying logic.

---

## Resources & References
* Ghidra Beginner’s Guide
* System Security & Cryptography Concepts
* Exponentiation by Squaring & Modular Arithmetic
* Introduction to Assembly Language for Reverse Engineering
* GDB Tutorial: Stepping Through Assembly
* Reversing with Ghidra & Understanding x86/x64 Assembly

---

## Tools Used
* **Ghidra**
* **IDA Pro**
* **Radare2**
* **GDB (GNU Debugger)**
* **Objdump**
* **Binwalk**
* **Strings**
* **Binary Ninja / Cutter**

---

## Learning Objectives
By the end of this project, you will be able to explain:
1. What static analysis is in the context of reverse engineering.
2. The importance of static analysis in malware analysis, security auditing, and debugging.
3. How disassembly and decompilation translate machine code into readable logic.
4. The key differences between executable formats (**PE**, **ELF**, and **Mach-O**).
5. Common static analysis tools and their practical use cases.
6. How control flow graphs (CFGs) map program execution flow.
7. Techniques for identifying vulnerabilities via pattern recognition and signature matching.
8. The role of header and cross-reference analysis in understanding binary structure and critical code paths.
9. The standard static analysis workflow from initial inspection to documentation.

---

## Requirements & Guidelines
* **Environment:** All analyses must be conducted safely in a controlled environment (e.g., a Kali Linux VM or sandbox).
* **Scripting:** All scripts must be executable on Kali Linux and utilize relative paths rather than hardcoded absolute paths.
* **Integrity:** Validate binary integrity before beginning analysis and ensure regular backups of working files.
* **Local Execution:** Strictly local analysis; no online tools or external services are permitted.
* **Target:** Focused on analyzing the designated `target_binary`.
