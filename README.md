# NetAudit-Lite: Lightweight Network Configuration Auditor

[![Language](https://img.shields.io/badge/Language-Python-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-V1.0%20(Prototype)-blue.svg)]()

##  Executive Summary for Scholarship Applications

I developed **NetAudit-Lite** as my first major step into network security. This Python tool is a lightweight auditor designed to quickly scan local networks for open ports and basic security misconfigurations. My motivation was to understand networking protocols firsthand and apply my programming skills to real-world infrastructure challenges. This project proves my commitment to applying knowledge preparing me for further study in engineering and security.

##  Technical Structure and Key Features

### 1. Core Technology

The project utilizes **Python 3.x** and relies on essential networking libraries:

* **socket:** Utilized for performing low-level port checks and establishing basic network communication.
* **argparse:** Employed to create a user-friendly and robust Command-Line Interface (CLI).
* **ipaddress:** Used for reliable parsing and validation of IP addresses and network ranges.

### 2. Main Capabilities

* **Targeted Port Scanning:** Fast and non-intrusive checking of commonly used ports for unexpected open status.
* **Basic Configuration Check:** Provides quick feedback on simple network security hygiene.
* **CLI Flexibility:** Allows the user to specify a particular IP address or a small range for focused analysis.

---

## Challenges and Learned Lessons (Crucial for Grant Committees)

Building **NetAudit-Lite** was a deep dive into low-level programming and infrastructure.

#### Key Challenges Faced:
1.  **Network Timeouts:** I struggled immensely with handling network latency and connection timeouts which often crashed the initial prototype. This required extensive research into robust error and exception handling.
2.  **Protocol Understanding:** Understanding the difference between TCP and UDP at the code level was a significant challenge initially required to correctly interpret scan results.

#### Technical and Personal Growth:
* **Socket Programming:** I mastered using Python's native socket library to communicate directly with ports gaining vital experience in low-level networking.
* **Resilience:** I learned the crucial necessity of building resilient code that can handle unpredictable external factors like network drops and unresponsive targets.
* **System View:** The project gave me a vital new perspective I now see computing not just as code but as interconnected layers of protocols and infrastructure.

---

## Installation and Usage Guide

### 1. Prerequisites

* Python 3.x or later.

### 2. Setup

Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/Aiman-Khadem/NetAudit-Lite](https://github.com/Aiman-Khadem/NetAudit-Lite)
cd NetAudit-Lite
pip install -r requirements.txt

