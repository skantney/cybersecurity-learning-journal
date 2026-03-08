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

