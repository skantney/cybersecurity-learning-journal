# DNS Basics

## What is DNS?

DNS (Domain Name System) translates domain names into IP addresses.

Example: 
 
```bash 

google.com -> 142.250.190.78
```

## Why it matters for cybersecurity

Attackers sometimes use DNS traffic to hide communication with infected systems.

## Commands

## DNS Investigation Example

Command used:

```bash

nslookup google.com

Result:
Name: google.com
Address: 142.250.190.78

This shows how DNS resolves a domain name to an IP address. In security investigations, analysts use this to identify infrastructure behind suspicious domains.
## Investigating the System

Once you can navigate the file system, the next step is gathering information about the environment you are working in.

**whoami** Displays the username of the current user. This is vital when first accessing a machine to see what level of privileges you have.

**uname -a** Prints detailed system information, including the Linux kernel version and the system architecture.

**df -h** Shows the amount of disk space available on the file system in a "human-readable" format (GB/MB).

**cat /etc/os-release** A specific command to view the distribution details (e.g., Ubuntu, Debian, or CentOS).
