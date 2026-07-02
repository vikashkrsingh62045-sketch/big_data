# Hadoop Word Count Using MapReduce

This project demonstrates the implementation of the **Word Count** application using the Hadoop MapReduce framework. The experiment involves creating a text file, storing it in HDFS, executing the built-in Hadoop Word Count program, and analyzing the generated output.

---

## Objective

To understand the working of the Hadoop MapReduce programming model by executing the Word Count application and generating word frequency statistics from an input text file.

---

## Prerequisites

- Ubuntu Linux
- Java installed
- Hadoop installed and configured
- HDFS running successfully
- Terminal access

---

## Experiment Overview

The experiment consists of the following stages:

- Creating an input text file
- Verifying the file contents
- Uploading the file to HDFS
- Executing the Hadoop MapReduce Word Count program
- Checking the output directory
- Viewing the generated word frequency results

---

## Workflow

```
Input Text File
        │
        ▼
Upload to HDFS
        │
        ▼
MapReduce Word Count
        │
        ▼
Processing by Hadoop
        │
        ▼
Output Directory in HDFS
        │
        ▼
Word Frequency Results
```

---

## Features

- Demonstrates Hadoop MapReduce execution
- Uses HDFS for distributed storage
- Processes text data efficiently
- Generates word frequency statistics
- Introduces the Mapper and Reducer workflow

---

## Learning Outcomes

After completing this experiment, you will be able to:

- Understand the Hadoop MapReduce architecture
- Store files in HDFS
- Execute built-in Hadoop applications
- Analyze MapReduce output
- Interpret word frequency results

---

## Applications

- Text analytics
- Log file analysis
- Document processing
- Search engine indexing
- Big Data processing
- Data mining

---

## Expected Output

The application generates a list of unique words along with their occurrence count in the input text file. The output is stored in the HDFS output directory after successful execution.

---

## Conclusion

The Hadoop MapReduce Word Count application successfully demonstrates distributed data processing using the MapReduce framework. The input file is processed in parallel, and the output contains the frequency of each word stored in HDFS. This experiment provides a practical understanding of Hadoop's distributed computing capabilities.

---

## Author

Prepared for **Big Data Analytics Laboratory**

---

## License

This project is intended for educational and learning purposes only.
