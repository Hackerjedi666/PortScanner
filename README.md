# PortScanner
# Port Scanner with Banner Grabbing

This Python script is a simple yet effective port scanner that not only scans open ports but also performs banner grabbing to identify services running on those ports. It uses multiprocessing for faster scanning and is easy to use.

## Features

- Scan a range of ports on a target IP address.
- Perform banner grabbing to detect services.
- Utilizes multiprocessing for faster scanning.
- User-friendly interface.

## Requirements

- Python 3.x
- The script uses Python's built-in libraries, so no additional installations are required.

## Usage

1. Clone the repository or download the `port_scanner_banner.py` script.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the script using the following command:

   ```python port_scanner_banner.py```

Follow the on-screen instructions to enter the target IP address, the number of threads to use, and the port range (default is 1-10,000).

*Example*
Enter the target IP: 192.168.1.100
Enter the number of threads to use (e.g., 10): 4

Open Ports:
Port 80: Apache HTTP Server 2.4.41 (Unix)
Port 22: OpenSSH 7.9p1 Ubuntu 10 (Ubuntu Linux)
Port 443: Nginx 1.14.0 (Ubuntu)
...
