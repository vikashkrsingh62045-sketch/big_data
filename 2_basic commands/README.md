# HDFS Basic File Operations

This project demonstrates the basic file operations in the Hadoop Distributed File System (HDFS). It covers creating directories, uploading files, listing directory contents, reading files, downloading files, and checking the replication factor.

---

## Objective

To understand and perform fundamental HDFS file operations using Hadoop command-line utilities.

---

## Prerequisites

- Hadoop installed and configured
- HDFS services running
- Sample text files available in the local directory
- Terminal access

---

## Operations Performed

### 1. Create Directory

Create a new directory named **demo** in HDFS.

---

### 2. Upload Files

Upload all sample text files to the **demo** directory in HDFS.

---

### 3. List Directory Contents

Verify that the files have been uploaded successfully by listing the contents of the **demo** directory and the HDFS root directory.

---

### 4. Read File Content

Display the contents of a text file stored in HDFS.

---

### 5. Download File

Download a file from HDFS to the local file system.

---

### 6. Check Replication Factor

Display the replication factor for all files stored in the **demo** directory.

---

## Learning Outcomes

After completing this experiment, you will be able to:

- Create directories in HDFS
- Upload files to HDFS
- List files and directories
- Read files stored in HDFS
- Download files from HDFS
- Verify the replication factor of HDFS files

---

## Project Workflow

```
Local Files
      │
      ▼
Upload to HDFS
      │
      ▼
HDFS /demo Directory
      │
      ├── List Files
      ├── Read File
      ├── Check Replication
      └── Download File
```

---

## Applications

- Distributed file storage
- Big Data processing
- Hadoop ecosystem practice
- HDFS file management
- Data storage and retrieval

---

## Author

Prepared for **Big Data Analytics Laboratory**

---

## License

This project is intended for educational and learning purposes only.
