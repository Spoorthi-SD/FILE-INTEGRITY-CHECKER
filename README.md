# FILE-INTEGRITY-CHECKER

COMPANY: CODETECH IT SOLUTIONS

NAME: Spoorthi S 

INTERN ID: CT12WPDY

DOMAIN: CYBER SECURITY & ETHICAL HACKING

DURATION: 12 WEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION OF THE TASK

The File Integrity Checker is a Python-based tool created to monitor changes in files by computing and comparing their hash values. It ensures the integrity of files by identifying unauthorized alterations.

Tools and Technologies Used

Python 3.x (Programming Language)

VSCode (Integrated Development Environment)

Hashlib Library (for hash calculations)

Git Bash (for executing Python scripts)

Development Platform
The entire project was developed in VSCode, a widely-used open-source code editor. VSCode offers a rich environment for writing, debugging, and testing Python code.

Use Cases
The File Integrity Checker is useful in a range of scenarios, including:

Data Security: Safeguard sensitive data by monitoring file changes.

Software Development: Ensure the integrity of code files to prevent unauthorized edits.

Network Security: Detect potential security threats by monitoring system file changes.

Digital Forensics: Investigate file modifications in the context of cybercrime investigations.

How It Functions

The user provides a file path and an expected hash value.

The tool computes the current hash value of the file using the Hashlib library.

The tool compares the current hash value with the expected hash value.

If both hash values match, the file is deemed intact. If they differ, the file has been altered.

Code Breakdown
The code contains two primary functions:

calculate_hash(file_path): Computes the SHA-256 hash value of a file.

check_file_integrity(file_path, expected_hash): Compares the current hash with the expected one to verify file integrity.

Reference Websites

Python Hashlib Documentation

Python Documentation

VSCode Documentation

Stack Overflow

GeeksforGeeks

Challenges Encountered
During development, I faced several challenges:

Understanding the Hashlib Library: I had to spend time learning how to use Hashlib to compute hash values effectively.

File Operations: I needed to understand how to read and write files in Python, dealing with various file modes and exceptions.

Error Handling: I implemented robust error handling to address issues like file not being found or invalid hash values.

#OUTPUT
