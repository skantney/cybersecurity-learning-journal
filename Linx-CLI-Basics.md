# Linux CLI Basics

## What is the Linux CLI?
The Command Line Interface (CLI) is a text-based interface used to interact with the computer's operating system. It allows for high-speed file management and system configuration without a GUI.

## Why it matters for cybersecurity
Most servers and security tools run on Linux. Mastering the CLI is essential for navigating compromised systems, analyzing logs, and automating security tasks.

## Essential Commands
**pwd**
Prints the "Working Directory," showing exactly where you are in the file system.

**ls -la**
Lists all files in a directory. The `-la` flags ensure you see hidden files (starting with a dot) and detailed file permissions.

**cd**
Used to change directories. Using `cd ..` moves you up one level in the folder hierarchy.

## File Investigation Example
Command used:
cat mission_brief.txt

Result:
THM{MISSION-FOUND}

This shows how to use the `cat` command to read the contents of a file directly in the terminal. In a real-world scenario, this is how an analyst might quickly inspect a suspicious script or configuration file.
