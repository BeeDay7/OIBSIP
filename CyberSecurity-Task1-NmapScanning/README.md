  # Basic Network Scanning with Nmap

## Objective
To perform a network scan to identify open ports and services running on a local machine using Nmap, and document findings with security analysis.

## Installation & Setup
1. Verified installation by running `nmap --version` in the Windows Command Prompt.
2. Output confirmed: Nmap version 7.80.

## Scan Execution
I ran the following commands against my local machine (`127.0.0.1`):
*   `nmap 127.0.0.1` (Basic Scan)
*   `nmap -sV 127.0.0.1` (Service Version Scan)
*   `nmap -O 127.0.0.1` (OS Detection Scan)

## Open Ports Analysis
*(Look at your terminal output and fill in the ports you found. Here is an example of what to write):*
*   **Port 135 (msrpc):** This is the Microsoft RPC service. While common on Windows, it can be a security risk if exposed to the internet without proper firewalls, as it has historically been targeted by attackers.
*   **Port 445 (microsoft-ds):** This is the SMB file sharing port. It is a major security risk if left open to the public because it is frequently targeted by ransomware (like WannaCry). It should be heavily firewalled.

## Ethical Use Guidelines
This scan was performed exclusively on my own local machine (127.0.0.1) for educational purposes. I did not scan external, public, or unauthorized systems.

## Demo Video
[Paste your LinkedIn video link here]
