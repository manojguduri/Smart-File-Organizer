# 📁 Smart File Organizer - Java Mini Project

A simple command-line Java utility that organizes files in a directory based on:
- File extension
- File size
- Creation date

Also includes a utility to restore all organized files back to the original home directory.

---

## 📦 Features

- ✅ Organize files by:
  - Extension (e.g., `.jpg`, `.pdf`, `.mp3`)
  - Size (e.g., `Small`, `Medium`, `Large`)
  - Creation date (e.g., `2025-05-27`)
- ✅ Automatically creates folders and moves files accordingly.
- ✅ Restore all files from subfolders back into the original directory.
- ✅ Handles name conflicts by appending a timestamp.

---

## 🛠️ Technologies Used

- Java SE 8+
- File I/O (`java.io.File`)
- Collections Framework
- Object-Oriented Programming
- Exception Handling

---

---

## 🚀 How to Run

1. **Compile the project:**
   ```bash
   javac projects/FileSort/*.java
2. **Run the file organizer:**
  ```bash
    java projects.FileSort.FileOrganizerMain

