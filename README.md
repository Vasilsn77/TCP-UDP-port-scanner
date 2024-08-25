# TCP-UDP-port-scanner
# 🌐 TCP/UDP Port Scanner

## 🔍 Overview
The **TCP/UDP Port Scanner** is a robust and intuitive tool designed for network security enthusiasts and professionals. It scans specified IP addresses or domains to identify open TCP and UDP ports, providing insights into the services running on them. The scanner comes with a user-friendly graphical interface, making it accessible to both beginners and experts.

## 🎯 Features
- **🌟 User-Friendly GUI:** An interactive interface built with Tkinter.
- **⚡ Multi-threaded Scanning:** Speed up your scans with up to 2048 concurrent threads.
- **🔐 SSL/TLS Support:** Secure port scanning with SSL/TLS integration, especially for port 443.
- **📊 Comprehensive Results:** Displays open ports and their corresponding services clearly and concisely.

## 🛠️ Getting Started

### 1. Prerequisites
Before you begin, ensure you have met the following requirements:
- **Python 3.x** installed on your machine.
- The following Python libraries:
  - `tkinter` (usually comes pre-installed with Python)
  - `socket`
  - `ssl`
  - `threading`
  - `queue`
  - `os`
  - `datetime`

### 2. Installation
1. **Clone the Repository**:
2. **Run the Script**
    python FINAL.py
3. **Launch the Application:**
    Double-click the FINAL.py file or run it from the command line.
4. **Enter the Target IP/Domain:**
    Input the target IP address or domain in the text field.
5. **Specify the Ports:**
    Enter specific ports (e.g., 80,443) or a range (e.g., 1:1024).
    Leave the field empty to scan all ports (1-65535).
6. **Start Scanning:**
    Click the "Scan" button to begin the port scan.
7. **View Results:**
    The results will be displayed in the text area, showing open ports and the services running on 
    them.
