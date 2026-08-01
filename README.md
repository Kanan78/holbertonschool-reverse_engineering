# 🔍 Reverse Engineering & ELF Analysis Toolkit

This repository contains a collection of Bash scripts and tools designed for analyzing ELF (Executable and Linkable Format) binary files, reverse engineering, and security analysis.

The main objective of this project is to quickly and effectively identify hidden functionality, anomalous sections, and potential security threats (such as obfuscated or malicious code) within binary files.

---

## 🚀 Features

* **ELF Header Extractor:** Extracts the file architecture (32/64-bit), endianness (byte order), magic number, and entry point address from an ELF binary.
* **Error Handling:** Automatically verifies file existence and validates whether the target file is a genuine ELF binary.
* **Modular Output:** Utilizes a centralized `messages.sh` structure to ensure consistent and clean output formatting.
* **Section Analysis:** Enables inspection of suspicious or executable sections within the binary.

---

## 📁 Project Structure

```text
.
├── get_entry_point.sh   # Main script to analyze the ELF header
├── messages.sh          # Helper script to format output messages
├── target_binary        # Sample binary file for analysis
└── README.md            # Documentation file
