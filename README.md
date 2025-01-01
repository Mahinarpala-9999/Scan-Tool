
# ScanTool

## Overview
ScanTool is a powerful utility designed to perform security and vulnerability scans using three robust tools: Nikto, Nmap, and Dirsearch. It simplifies the process of performing web server scans, network scans, and directory enumeration in a unified interface.

## Features
- **Nikto Scan**: Perform web server scans to identify vulnerabilities, outdated software, and security misconfigurations.
- **Nmap Scan**: Conduct network scans to discover open ports, running services, and potential vulnerabilities.
- **Dirsearch Scan**: Perform directory enumeration to identify hidden directories and files on a web server.
- **Comprehensive Scanning**: Supports executing all three scans simultaneously or individually, depending on the use case.

## Installation

### Prerequisites
Ensure the following are installed on your system:
- [Python](https://www.python.org/)
- Nikto
- Nmap
- Dirsearch

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ScanTool.git
   cd ScanTool
   ```
2. Install required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure Nikto, Nmap, and Dirsearch are installed and added to your system's PATH.

## Usage

### Running Scans
Use the following commands to perform individual or combined scans:

- **Nikto Scan**:
  Perform a web server vulnerability scan.
  ```bash
  python scan_tool.py --nikto --url <target-url>
  ```

- **Nmap Scan**:
  Conduct a network scan.
  ```bash
  python scan_tool.py --nmap --target <target-ip>
  ```

- **Dirsearch Scan**:
  Enumerate directories on a web server.
  ```bash
  python scan_tool.py --dirsearch --url <target-url>
  ```

- **All Scans**:
  Execute all three scans sequentially.
  ```bash
  python scan_tool.py --all --target <target-ip> --url <target-url>
  ```

### Example
To scan a web server at `http://example.com` using all tools:
```bash
python scan_tool.py --all --url http://example.com
```

## Dependencies
- Nikto
- Nmap
- Dirsearch
- Python (for executing the script)

## Contribution
Feel free to fork this repository, submit pull requests, or suggest improvements through issues.

## License
This project is licensed under the [MIT License](LICENSE).

## Author
[Your Name]

## Acknowledgments
Special thanks to the creators of Nikto, Nmap, and Dirsearch for their amazing tools.
```

