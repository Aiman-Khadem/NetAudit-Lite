NetAudit-Lite is a fast and lightweight Python tool for scanning open ports and analyzing basic network misconfigurations. It uses low-level socket programming and multi-threading to perform reliable and rapid host scans.

Core Features

Low-level Python socket programming

Concurrent scanning using ThreadPoolExecutor

Adjustable timeout system

Real-time status reporting (OPEN / CLOSED / ERROR)

Supports scanning single hosts or small IP ranges

Error handling for timeouts, DNS issues, and refused connections


Technical Concepts Used

TCP & UDP port behavior

Socket connection states

Multi-threading concurrency

Network latency resilience

CLI-based architecture


What I Learned

Real behavior of unstable network environments

How latency, packet loss, and timeouts affect scanning

Building resilient code with proper Exception Handling

The necessity of deeper study in OS internals, protocols, and secure scanning methodologies


 Future Improvements

Banner grabbing

TCP fingerprinting

Non-intrusive scan modes

Exporting scan results to files
