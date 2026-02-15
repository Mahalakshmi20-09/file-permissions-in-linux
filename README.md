> Linux Security Project | System Hardening | Least-Privilege Enforcement

# Linux File System Hardening: Least-Privilege Enforcement

## Overview

This project demonstrates a Linux file system security hardening exercise focused on enforcing the Principle of Least Privilege (PoLP). The objective was to analyze file and directory permissions, identify insecure configurations, and remediate access control risks using command-line tools.

## Key Steps

- Performed permission audit using 'ls -la' to inspect file and directory configurations.
- Identified insecure world-writable file permissions ('-rw-rw-rw-').
- Removed unauthorized write access using 'chmod o-w filename'.
- Applied restrictive permission settings ('chmod 440') to secure hidden and archived files.
- Enforced least-privilege principles to strengthen file-level access control.

## Security Concepts Demonstrated

- Principle of Least Privilege (PoLP)
- Linux File Permission Model
- Access Control Enforcement
- System Hardening
- Defensive Security Practices

## Tools Used

- Linux Command Line
- chmod
- ls
- File Permission Auditing


## Author

JM Mahalakshmi 
Cybersecurity Enthusiast | Linux Security | Defensive Security Engineering
