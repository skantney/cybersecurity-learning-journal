# Linux CLI Basics

## What is the Linux CLI?
The Command Line Interface (CLI) is a text-based interface used to interact with the computer's operating system. It allows for high-speed file management and system configuration without a GUI.

## Why it matters for cybersecurity
Most servers and security tools run on Linux. Mastering the CLI is essential for navigating compromised systems, analyzing logs, and automating security tasks.

## Commands

### Check Current Directory
```bash
pwd
```
Prints the working directory, showing exactly where you are in the file system.

### List Files
```bash
ls -la
```
Lists all files in a directory. The `-la` flags display hidden files and detailed permissions.

### Change Directory
```bash
cd directory_name
```
Moves you into another directory. Using `cd ..` moves up one level.

### Read a File
```bash
cat mission_brief.txt
```
Displays the contents of a file directly in the terminal.

### Search File Content
```bash
grep "keyword" filename
```
Searches a file for specific text. Security analysts often use `grep` to find suspicious activity in logs.
## Linux Investigation Example

Objective: Read the contents of a file discovered during a system investigation.

Command used:

```bash
cat mission_brief.txt
```

Result:  
The command displayed the contents of the file directly in the terminal, allowing the investigator to quickly review the information without opening a GUI editor.

Cybersecurity relevance:  
Analysts often use `cat` to quickly inspect log files, configuration files, or suspicious scripts on a compromised system.

## Lab Reference
Platform: TryHackMe  
Room: Linux Command Line Basics  
Skills Practiced: Navigation, file inspection, directory management
