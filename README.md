# Automatic File Organizer 📂

A simple automation utility written in Python that scans your Downloads folder and automatically organizes files into neat, categorized subfolders based on their file extensions.

---

## Features

* **Automated Categorization**: Sorts files into specific categories such as **Images**, **Documents**, **Videos**, **Music**, **Archives**, and **Scripts**.
* **Fallback Handling**: Moves any unrecognized file formats safely into an **Others** folder[cite: 4].
* **Dynamic Directory Creation**: Automatically creates category subfolders within your target directory if they do not already exist[cite: 4].

---

## Prerequisites & Installation

* Requires **Python 3** (no external libraries or `pip` installations are required since it uses built-in modules `os` and `shutil`[cite: 4]).

---

## How to Run

1. Download or copy the code into a file named `Task 4.py`[cite: 4].
2. **Note on Safety**: By default, the script targets your system's `~/Downloads` folder[cite: 4]. If you wish to test it safely first, modify the `DOWNLOADS_FOLDER` variable to point to a test directory.
3. Open your terminal or command prompt and run the script:

```bash
python "Task 4.py"
