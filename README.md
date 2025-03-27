Port Scanner - Basic Python Socket Tool
=======================================

Overview
--------
This is a simple Python-based port scanning tool that checks whether a specific TCP port is open on a given IP address. It uses Python's built-in `socket` module to attempt a connection and returns the status of the port.

This is a great beginner tool for learning about sockets, networking, or for use in basic internal network diagnostics.

How It Works
------------
1. Prompts the user to input an IP address and a port number.
2. Attempts to connect to the specified port on the IP.
3. Reports whether the port is open or closed based on the success of the connection.

Requirements
------------
- Python 3.x

No external libraries are required.

Usage
-----
1. Clone or download the script from the repository.
2. Open a terminal and run the script:

```bash
python port_scanner.py
