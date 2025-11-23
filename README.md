

[![Language](https://img.shields.io/badge/Language-Python-blue.svg)](/)
[![Status](https://img.shields.io/badge/Status-Prototype%20(Protocol%20Resilience%20Phase)-orange.svg)](/)

---

## Executive Summary (For Scholarship Reviewers)

**NetAudit-Lite** is a foundational tool I developed in Python to perform quick audits of local networks, specifically targeting open ports and basic security misconfigurations. This project was a direct application of my programming skills to real-world infrastructure problems. Crucially, its development revealed the profound fragility of networking code when faced with unpredictable network latency and connection failures. Overcoming these **resilience challenges** formed the core learning experience, underscoring the vital need for formal academic training in network architecture and low-level protocol theory.

---
##  Technical Overview & Core Features

### 1. Core Technology Stack
The project is built on **Python 3.x** and relies on native, low-level networking libraries:

* **socket:** Used for raw, low-level port checks and handling direct network communication.
* **argparse:** Implements a professional and flexible Command-Line Interface (CLI).
* **ipaddress:** Ensures reliable parsing and validation of IP addresses and network ranges.

### 2. Main Capabilities
* **Targeted Port Scanning:** Non-intrusive checking of specified ports.
* **Configuration Feedback:** Provides immediate, high-level feedback on network security hygiene.
* **Robust CLI:** Supports flexible targeting of single IP addresses or small ranges.

---

##  Motivation, Challenges, and Academic Growth

### Mastering Resilience: The Fragility of Networks and the Limits of Self-Taught Protocol Knowledge

My development of **NetAudit-Lite** began with a simple motivation: the desire to visualize and truly understand the network layers I interact with daily. However, this project quickly became a struggle with the **unstable external environment**.

The initial prototype of the program was **Extremely Fragile**, constantly crashing due to **Random Connection Timeouts** from unresponsive targets or general network sluggishness. I realized that networks are not based on 'dry' logic; they are a volatile environment that demands **Resilient Code**.

This core challenge forced me to dive deep into advanced **Error and Exception Handling** concepts in Python. I successfully built mechanisms to gracefully manage unexpected scenarios (such as outright connection refusal or sudden disconnection), enabling the tool to complete scans even when faced with difficult targets. This shift in methodology—from simply writing functions to engineering resilience—was my most significant achievement in this project.

#### The Shortcomings That Underline My Need for Study:

Despite my success in building resilient code, I recognize that **NetAudit-Lite still suffers from a critical lack** of the theoretical foundation required to elevate it to a professional-grade tool:

1.  **Protocol Blindness (Lack of Deep Understanding):** The current code relies heavily on the abstractions provided by the `socket` library, which conceals the crucial details of **TCP and UDP**. To provide accurate and meaningful scan results, I need a deeper academic understanding of how these protocols are constructed at the byte level and how to interpret non-standard responses.
2.  **Lack of System Methodology:** I currently lack sufficient understanding of how **Operating Systems** manage ports and sockets system-wide. This knowledge is essential for developing tools that are not only effective but also **resource-light** and seamlessly integrated with the host environment.
3.  **Balancing Scanning and Intrusiveness:** The basic techniques I currently use are relatively simple and could be considered intrusive in certain environments. I require advanced study in **Network Security** and less aggressive scanning techniques to ensure the tool is responsible, ethical, and applicable in professional contexts.

The challenges in **NetAudit-Lite** taught me that **network programming is not just about library functions; it is a strict application of protocol theory**. I am convinced that studying in your academic program will provide me with the systematic theoretical knowledge necessary to fill these gaps and transform this project from a light auditor into a highly credible and robust networking tool.
