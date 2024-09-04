# Packet-Sniffer
Packet Sniffer is a Python tool developed by Sworup Kumar Sahu for capturing and analyzing network packets. This tool is designed for educational purposes and demonstrates basic packet sniffing techniques.

# Features
* Packet Capture: Captures network packets in real-time.
* Information Display: Shows source and destination IP addresses, protocol types, and payload data.
* Protocol Support: Handles TCP, UDP, and raw payloads.

# Installation
* Clone the Repository:
```
https://github.com/sworup1999/Packet-Sniffer
cd packet-sniffer.py
```
# Install Dependencies:
* Make sure you have Python installed, then install the required library:
```
pip install scapy
```
# Usage
* Run the script to start capturing and analyzing packets:
```
sudo python packet_sniffer.py
```
* Note: On Windows, you might need to run the script from an elevated command prompt.


# Important Notes
Ethical Use: This tool is intended for educational purposes. Always use it in a controlled environment with explicit permission. Unauthorized packet sniffing is illegal and unethical.
Network Interface: The script captures packets from all network interfaces by default. To specify a particular interface, use the ```iface``` argument in the ```sniff()``` function.

# Future Enhancements
* Filtering: Add packet filtering to capture specific types of traffic.
* GUI: Develop a graphical user interface for easier interaction and analysis.
* Advanced Analysis: Implement advanced packet analysis features and protocol decoders.
