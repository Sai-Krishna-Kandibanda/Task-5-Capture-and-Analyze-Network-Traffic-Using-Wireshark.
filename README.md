# Task-5-Capture-and-Analyze-Network-Traffic-Using-Wireshark.

## Objective
To capture live network traffic using Wireshark, identify three different protocols in action (DNS, TCP, ICMP), and understand their roles in communication.

## What is Wireshark?
Wireshark is an open-source network protocol analyser that lets you see what's happening on your network at a detailed packet level. It's used by network administrators, security analysts, and penetration testers for troubleshooting and analysis.

## Tools Used
- Wireshark (latest version)
- Windows 10 PC
- Chrome Browser
- Snipping Tool (for screenshots)

## Steps Performed
1. Installed Wireshark and launched the application.
2. Selected active network interface (Wi-Fi 2).
3. Started live capture.
4. Generated traffic:
   - Browsed websites(roadmap.sh).
5. Stopped capture after ~2 minutes.
6. Filtered packets by protocol (`dns`, `tcp`, `icmp`).
7. Analysed packet details for each protocol.
8. Saved capture as `network-capture.pcap`.
9. Documented steps and took screenshots.

## Protocols Identified
- **DNS** – Resolves domain names to IP addresses (e.g., `www.google.com` → IP).
- **TCP** – Core protocol for reliable communication between systems; used for web, email, etc.
- **ICMP** – Used for network testing and diagnostics (`ping`), showing reachability and response times.

## What I Learned
- How to capture and filter traffic for targeted analysis.
- The purposes of DNS, TCP, and ICMP in real-world network operations.
- Using Wireshark filters to focus on relevant traffic and exclude noise.
