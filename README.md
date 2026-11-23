
# Mental Health Tracker

### A C++ Console Application for Mood Tracking and Analysis

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![OOP](https://img.shields.io/badge/Object--Oriented_Programming-1F2937?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-2563EB?style=for-the-badge)

---

## Overview

Mental Health Tracker v6.5 is a console-based application developed in C++ to demonstrate object-oriented programming, file handling, and interactive software design.

The application allows users to record mood ratings, review previous sessions, view text-based statistics, and interact with a simple rule-based chatbot.

This is an educational software project rather than a medical or clinical assessment tool.

## Key Features

| Feature | Description |
|---|---|
| User Registration | Create a local user record |
| User Login | Access saved records using a username and PIN |
| Mood Tracking | Record mood ratings on a scale of 1–10 |
| Mood History | Store and review previous sessions |
| Advice System | Display predefined suggestions from text files |
| Rule-Based Chatbot | Generate responses based on recognized keywords |
| ASCII Analytics | Visualize mood ratings in the terminal |
| Session Comparison | Compare recorded values across sessions |
| OOP Implementation | Demonstrate inheritance, polymorphism, and operator overloading |

## Technical Implementation

The application demonstrates the following C++ concepts:

- Classes and objects
- Constructors and destructors
- Encapsulation
- Inheritance
- Runtime polymorphism
- Operator overloading
- Static data members
- File handling using fstream
- Arrays and strings
- Menu-driven programming

## Project Structure

```text
Mental-Health-Tracker-CPP/
|
|-- MHT v6.5.cpp
|-- Happy.txt
|-- Angry.txt
|-- Anxious.txt
|-- Calm.txt
|-- Depressed.txt
|-- Focused.txt
|-- Motivated.txt
|-- Neutral.txt
|-- Stressed.txt
|-- Tired.txt
|-- README.md
|-- LICENSE
|-- .gitignore
|-- Project documentation (PDF)
|-- Sample outputs (PDF)
```

## Installation and Execution

### Requirements

- A C++ compiler supporting C++11 or later
- Windows, Linux, or macOS
- A terminal or compatible C++ IDE

### Clone the Repository

```bash
git clone https://github.com/miksi0078/Mental-Health-Tracker-CPP.git

cd Mental-Health-Tracker-CPP
```

### Compile

```bash
g++ -std=c++17 "MHT v6.5.cpp" -o tracker
```

### Run

On Windows:

```bash
.\tracker.exe
```

On Linux or macOS:

```bash
./tracker
```

Keep the mood-related `.txt` files in the working directory when running the application.

## Application Workflow

1. Register a new user or sign in.
2. Choose an option from the main menu.
3. Record a mood score and select an emotion.
4. Read the corresponding predefined advice.
5. Optionally submit a post-session mood rating.
6. Review saved history or terminal-based graphs.
7. Exit the application.

## Current Limitations

This is an academic demonstration and is not production-ready.

- Authentication data is stored locally without secure password hashing.
- The chatbot uses keyword matching, not a trained AI model.
- The advice system uses predefined text rather than clinical reasoning.
- The application does not provide medical diagnosis or treatment.
- Additional input validation and automated tests are needed.

Use demonstration accounts only. Do not enter real passwords or sensitive personal information.

## Future Improvements

- Secure authentication and password hashing
- Improved input validation
- Modular source-code organization
- Automated unit testing
- Improved data storage architecture
- Graphical user interface

These are planned improvements, not implemented features.

## Documentation

The repository includes project documentation and example output files for reference.

## Author

**Muhammad Ilyas**

BS Artificial Intelligence  
University of Central Punjab, Lahore

GitHub: [miksi0078](https://github.com/miksi0078)

## License

This project is distributed under the MIT License.
See the [LICENSE](LICENSE) file for details.
