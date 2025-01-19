# cph-leetcode-helper
A VS code extension for managing Leetcode problems
Competitive Programming Helper (CPH) - LeetCode Extension
The CPH-LeetCode Helper is a VS Code extension designed to streamline competitive programming workflows, specifically for LeetCode problems. It offers automated test case management, local code execution, and data structure utilities for seamless problem-solving.

Features
Automated Test Case Management:

Fetch test cases directly from LeetCode using problem URLs.
Save test cases in an organized folder structure for reusability.
Add and manage custom test cases easily.
Local Code Execution:

Execute solutions in C++ and Python against saved test cases.
Debug and compare results locally before submission.
Data Structure Utilities:

Built-in support for common data structures:
Linked Lists
Doubly Linked Lists
Binary Trees
Workspace Automation:

Automatically generates a workspace with structured folders for:
Test cases
User solutions
Predefined utility scripts
Requirements
Software Dependencies
Node.js:

Required for running helper scripts.
Install globally on your system: Download Node.js
Install Puppeteer for fetching LeetCode test cases:
bash
Copy
Edit
npm install puppeteer
Programming Languages:

C++: Ensure you have a G++ compiler installed.
Python: Version 3.x is recommended.
VS Code Extension Settings
No additional configuration is needed after installing this extension.

How to Use
1. Setting Up
Install this extension from the VS Code Marketplace.
Ensure all dependencies (Node.js, Puppeteer, compilers) are installed.
2. Fetching Test Cases
To fetch test cases for a specific problem:

Open the command palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
Search for and execute the command: CPH: Fetch Test Cases.
Provide the LeetCode problem URL when prompted.
Test cases will be saved in the testcases directory of the workspace.

3. Writing Your Solution
Edit the solution file:

C++: Open user_solutions/main.cpp.
Python: Open user_solutions/main.py.
4. Running Test Cases
Execute your solution against the fetched test cases:

Open the command palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
Search for and execute the command: CPH: Run Code.
Select the desired language (C++ or Python) and test case folder.
Extension Settings
This extension does not currently include customizable settings. Future releases may provide options for:

Selecting default programming languages.
Customizing the workspace structure.
Known Issues
Currently supports only C++ and Python.
LeetCode account login is not integrated—public problems only.
Release Notes
1.0.0
Initial release with the following features:
Test case fetching and saving.
Local solution execution.
Linked list, doubly linked list, and binary tree utilities.
Additional Details
Data Structure Utilities
File: ListNode.cpp/.h
Provides functions to handle data structures such as:

Linked Lists:
Conversion from arrays to linked lists.
Traversal and printing of linked list elements.
Binary Trees:
Conversion from arrays to trees.
Traversals: Preorder, Inorder, and Postorder.
Utility Functions:
stringToArray for parsing array inputs.
arrayToLinkedList for constructing linked lists.
File: ListNode.py
Equivalent Python implementation for the above functionalities.

Required Modules
Node.js: puppeteer
Python: None additional, standard library suffices.
For More Information
Explore:

VS Code Extension API
Markdown Syntax Guide
Enjoy solving LeetCode problems efficiently with CPH-LeetCode Helper! 🎉
