# DNS Basics

## What is DNS?

DNS stands for Domain Name System.

It translates human-readable domain names into IP addresses that computers use to locate servers on the internet.

Example:

google.com → 142.250.190.78

Without DNS, we would have to memorize IP addresses for every website.

---

## How DNS Works (Simplified)

When you type a website into your browser:

1. Your computer asks a DNS resolver for the IP address.
2. The resolver checks if it already knows the answer.
3. If not, it queries DNS servers on the internet.
4. The correct IP address is returned.
5. Your computer connects to that server.

The website loads.

---

## Why DNS Matters for Cybersecurity

DNS traffic is often trusted by networks, which makes it attractive for attackers.

Malware can use DNS to:

- communicate with command-and-control servers
- hide data exfiltration
- redirect users to malicious websites

Security teams monitor DNS logs to detect suspicious activity.

---

## Useful Commands

### nslookup
Queries DNS records.

Example:

nslookup google.com

### dig
Advanced DNS lookup tool used on Linux.

Example:

dig google.com

---

## Key Takeaway

DNS is like the phonebook of the internet. Understanding how it works helps security analysts detect suspicious network behavior.
