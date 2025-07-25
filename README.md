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
1. Ensure Python 3.6+ is installed on your system. Verify with:
   ```bash
   python --version
Clone the repository to your local machine:
bash

Collapse

Wrap

Run

Copy
git clone https://github.com/<your-username>/<repository-name>.git
Navigate to the project directory:
bash

Collapse

Wrap

Run

Copy
cd <repository-name>
(Recommended) Create and activate a virtual environment to isolate dependencies:
bash

Collapse

Wrap

Run

Copy
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
No additional dependencies are required, as the tool uses Python's standard library.
Usage Examples
Scan the default port range (1-1024) on a target IP or hostname:
bash

Collapse

Wrap

Run

Copy
python port_scanner.py 192.168.1.1
Scan a specific port range (e.g., ports 20-80) on a target:
bash

Collapse

Wrap

Run

Copy
python port_scanner.py example.com -s 20 -e 80
Example output:
text

Collapse

Wrap

Copy
[*] Scanning 192.168.1.1 from port 1 to 1024
[*] Started at 2025-07-25 21:19:00
[+] Open ports found:
PORT    STATE    SERVICE
22      open     SSH-2.0-OpenSSH_8.9p1 Ubuntu-3
80      open     Apache/2.4.52 (Ubuntu)
[*] Scan completed at 2025-07-25 21:19:05
Ethical Use Disclaimer
This tool is intended strictly for educational purposes and authorized network security assessments. Use it only on systems and networks where you have explicit permission to perform scanning activities. Unauthorized port scanning or network reconnaissance is illegal and unethical, and may violate local laws or regulations. The developers are not responsible for any misuse or damage caused by this tool.

Show in sidebar
