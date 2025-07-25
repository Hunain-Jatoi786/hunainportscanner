# Advanced Port Scanner

## Description
A multi-threaded port scanner written in Python that scans a target host for open ports and attempts to grab service banners for open ports. This tool is designed for educational purposes and network security assessments.

## Features
- Multi-threaded port scanning for improved performance
- Banner grabbing for open ports
- Customizable port range
- Clean console output with timestamp
- Error handling for invalid hosts and interruptions

## Installation Steps
1. Ensure Python 3.6+ is installed on your system.
2. Clone the repository:
   ```bash
   git clone <repository-url>
Navigate to the project directory:
cd <project-directory>
(Optional) Create and activate a virtual environment:
Copy
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
No additional dependencies are required as the tool uses Python's standard library.
Usage Examples
Scan ports 1-1000 on a target IP:
Copy
python port_scanner.py 192.168.1.1
Scan a specific port range (e.g., 20-80):
Copy
python port_scanner.py example.com -s 20 -e 80
Screenshot
<img src="screenshot.png" alt="Port Scanner Output">
Note: Replace with actual screenshot of the tool in action.
