# Hadoop Installation (Single Node Setup)

A step-by-step guide to install and configure Hadoop in Single Node mode on Ubuntu.

## Prerequisites

- Ubuntu 20.04/22.04
- Internet connection
- Sudo privileges

---

## Step 1: Update Ubuntu

Update the package list and upgrade installed packages.

---

## Step 2: Install Java

- Check if Java is installed.
- Install OpenJDK 11.
- Verify the installation.
- Find the JAVA_HOME path.

---

## Step 3: Create Hadoop User

- Create a dedicated Hadoop user.
- Add the user to the sudo group.
- Switch to the Hadoop user.

---

## Step 4: Configure SSH

- Install OpenSSH Server and Client.
- Generate SSH keys.
- Enable passwordless SSH.
- Test SSH connection.

---

## Step 5: Download Hadoop

- Download Hadoop 3.4.1.
- Extract the archive.
- Rename the extracted directory to `hadoop`.

---

## Step 6: Configure Environment Variables

Update the `.bashrc` file by setting:

- JAVA_HOME
- HADOOP_HOME
- HADOOP_INSTALL
- HADOOP_MAPRED_HOME
- HADOOP_COMMON_HOME
- HADOOP_HDFS_HOME
- YARN_HOME
- HADOOP_COMMON_LIB_NATIVE_DIR
- PATH
- HADOOP_OPTS

Reload the shell configuration.

---

## Step 7: Configure `hadoop-env.sh`

Set the `JAVA_HOME` variable in the Hadoop environment configuration file.

---

## Step 8: Configure `core-site.xml`

Configure the default Hadoop filesystem.

---

## Step 9: Configure `hdfs-site.xml`

Configure:

- Replication factor
- NameNode storage directory
- DataNode storage directory

---

## Step 10: Create HDFS Directories

Create directories for:

- NameNode
- DataNode

---

## Step 11: Configure `mapred-site.xml`

- Copy the template.
- Configure MapReduce to use YARN.

---

## Step 12: Configure `yarn-site.xml`

Configure NodeManager auxiliary services for MapReduce.

---

## Step 13: Format the NameNode

Initialize the Hadoop filesystem by formatting the NameNode.

---

## Step 14: Start Hadoop Services

Start:

- HDFS
- YARN

---

## Step 15: Verify Running Services

Verify that Hadoop daemons are running using the Java Process Status tool.

Expected services include:

- NameNode
- DataNode
- SecondaryNameNode
- ResourceManager
- NodeManager

---

## Step 16: Check Hadoop Version

Verify the installed Hadoop version.

---

## Step 17: Access Hadoop Web Interfaces

- **NameNode UI:** `http://localhost:9870`
- **ResourceManager UI:** `http://localhost:8088`

---

## Step 18: Stop Hadoop Services

Stop:

- YARN
- HDFS

---

## Quick Verification Checklist

- Java installed successfully
- Hadoop downloaded and extracted
- Environment variables configured
- SSH passwordless login working
- Configuration files updated
- NameNode formatted successfully
- HDFS started
- YARN started
- Hadoop services visible in JPS
- Hadoop Web UI accessible

---

## Project Structure

```
hadoop/
├── bin/
├── sbin/
├── etc/
│   └── hadoop/
│       ├── core-site.xml
│       ├── hdfs-site.xml
│       ├── mapred-site.xml
│       ├── yarn-site.xml
│       └── hadoop-env.sh
└── lib/
```

---

## Author

Prepared for **Big Data Analytics Laboratory**

---

## License

This project is intended for educational purposes only.
