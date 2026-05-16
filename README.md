# python-port-scanner
A fast and simple CLI port scanner written in Python 3.
# Python CLI Port Scanner 🚀

A simple, lightweight, and efficient Command Line Interface (CLI) port scanner written in Python 3. It runs natively on any system (Linux, Windows, macOS) without requiring any external libraries.

## 🌟 Features
* **Zero Dependencies**: Written purely in standard Python 3. No `pip install` needed.
* **Multi-target support**: Scan multiple IP addresses or domains simultaneously by separating them with commas.
* **Timeout Handling**: Built-in exception and timeout handling to prevent the script from freezing on closed ports.

## 🛠️ Installation

Since the script uses only built-in Python modules, you just need to clone the repository:

```bash
git clone https://github.com
cd python-port-scanner
```

## 🚀 Usage

Run the script using Python 3:
```bash
python3 portscanner.py
```

### Example:
```text
[*] Enter Target to scan (split them by ','): 127.0.0.1, 192.168.1.1
[*] Enter the number of ports to scan: 100

[*] Scanning multiple targets...

[*] Starting scan for 127.0.0.1
[+] Port 22 is OPEN
[+] Port 80 is OPEN
```

## 📝 License
This project is for educational purposes only.
