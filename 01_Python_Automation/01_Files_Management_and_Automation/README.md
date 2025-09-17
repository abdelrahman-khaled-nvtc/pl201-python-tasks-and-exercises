# Chapter 4 — File Management & Automation

This chapter focuses on **files**, **directories**, and **automation** using ONLY:
- `open()` / `with` (context managers)
- `os`, `os.path`
- `shutil`
- `re`
- `try/except` (e.g., `FileNotFoundError`)

---

## Learning Objectives

By completing this chapter, you will be able to:

### **File Operations**
- **Read files** using `open()` and context managers (`with` statements)
- **Write and append** data to files with proper encoding
- **Process file contents** line by line and handle different file formats
- **Handle file errors** gracefully using try/except blocks

### **Directory Management**
- **List directory contents** and navigate folder structures
- **Check file/directory existence** before performing operations
- **Build cross-platform file paths** using `os.path.join()`
- **Create, rename, and delete** files and directories safely

### **Batch Processing & Automation**
- **Process multiple files** in batches (filtering by extension, reading contents)
- **Rename multiple files** with patterns and prefixes
- **Automate file organization** tasks programmatically

### **Archive Operations**
- **Compress folders** into archive files (ZIP format)
- **Extract archives** to specific directories
- **Manage backup operations** for important data

### **Pattern Matching & Log Analysis**
- **Search for specific patterns** in text files using regular expressions
- **Analyze log files** to find error messages and important information
- **Filter and process** large text files efficiently

### **Error Handling & Best Practices**
- **Implement robust error handling** for file operations
- **Use context managers** for safe file handling
- **Follow Python best practices** for file and directory operations
- **Write clean, maintainable code** for automation tasks

---

## Folder Structure

```
01_Files_Management_and_Automation/
├─ README.md                              # (this file)
├─ 01_Open_Print_File/                    # Exercise 1: Open & Print File
├─ 02_Write_File/                         # Exercise 2: Write to File
├─ 03_Append_Data/                        # Exercise 3: Append Data
├─ 04_Read_Lines_Loop/                    # Exercise 4: Read Lines in a Loop
├─ 05_List_Directory/                     # Exercise 5: List Directory
├─ 06_Check_Path_Exists/                  # Exercise 6: Check Path Exists
├─ 07_Join_Paths/                         # Exercise 7: Join Paths
├─ 08_Rename_File/                        # Exercise 8: Rename File
├─ 09_Delete_File/                        # Exercise 9: Delete File
├─ 10_Delete_Folder/                      # Exercise 10: Delete Folder
├─ 11_Batch_Print_Txt/                    # Exercise 11: Batch Print .txt Files
├─ 12_Rename_With_Prefix/                 # Exercise 12: Rename with Prefix
├─ 13_Compress_Folder/                    # Exercise 13: Compress Folder
├─ 14_Extract_Folder/                     # Exercise 14: Extract Folder
├─ 15_Handle_Missing_File/                # Exercise 15: Handle Missing File
├─ 16_Find_ERROR_in_Logs/                 # Exercise 16: Find ERROR in Logs
└─ 17_Quick_Backup/                       # Exercise 17: Quick Backup
```

---

## How to Use

### Prerequisites
- Python 3.10+
- A terminal (Windows PowerShell, macOS Terminal, or Linux shell)

### Getting Started

1. **Navigate to an exercise:**
   ```bash
   cd 01_Open_Print_File
   ```

2. **Read the task instructions:**
   ```bash
   cat TASK.md
   ```

3. **Complete the exercise:**
   - Edit `starter.py` to implement the required functionality
   - Keep solutions concise (1-10 lines per exercise)
   - Use only the modules specified in each exercise

4. **Run your solution:**
   ```bash
   python starter.py
   ```

### Exercise Structure
Each exercise folder contains:
- `TASK.md` — Clear instructions for the exercise
- `starter.py` — Minimal code template to complete
- Data files — Sample files needed for the exercise (varies by exercise)

---

## Exercise List

1. **Open & Print File** — Read and display file contents
2. **Write to File** — Create and write data to files
3. **Append Data** — Add content to existing files
4. **Read Lines in a Loop** — Process file contents line by line
5. **List Directory** — Explore directory contents
6. **Check Path Exists** — Verify file and directory existence
7. **Join Paths** — Build file paths safely across platforms
8. **Rename File** — Change file names programmatically
9. **Delete File** — Remove files safely
10. **Delete Folder** — Remove directories and their contents
11. **Batch Print .txt Files** — Process multiple text files
12. **Rename with Prefix** — Add prefixes to multiple files
13. **Compress Folder** — Create archive files
14. **Extract Folder** — Extract archive contents
15. **Handle Missing File** — Implement error handling for file operations
16. **Find ERROR in Logs** — Search for specific patterns in log files
17. **Quick Backup** — Create backup copies of important files

---

## Troubleshooting

- **`python` vs `python3`**: On macOS/Linux, you may need `python3`
- **Permission denied**: Ensure you have write permissions in the exercise directory
- **Path issues on Windows**: Prefer PowerShell and quote paths with spaces:
  ```powershell
  cd "01_Open_Print_File"
  python starter.py
  ```

---

## Allowed Tools (Chapter Compliance)

This chapter intentionally restricts to:
- `open()/with`
- `os`, `os.path`
- `shutil`
- `re`
- `try/except`

Stick to these to build mastery in core file operations and automation.

Happy coding!