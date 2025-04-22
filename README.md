# CodeAlpha_Project_Sniffer
🕵️ Sniffer
Sniffer is a lightweight network packet sniffer tool built for monitoring and analyzing network traffic. It captures and logs packets on a network interface, helping developers, network engineers, and cybersecurity professionals gain insights into data flow.

🚀 Features
🧲 Real-time packet capture

📦 Supports Ethernet, TCP, UDP, ICMP, and more

🔍 Packet filtering by protocol or port

📄 Logs captured data in human-readable format

💡 Lightweight and easy to use

🛠️ Installation
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/sniffer.git
cd sniffer
Install dependencies (if applicable):

bash
Copy
Edit
pip install -r requirements.txt  # for Python-based sniffers
📦 Usage
Basic usage:

bash
Copy
Edit
sudo python sniffer.py
Options:

bash
Copy
Edit
-h, --help            show help message
-i, --interface       specify network interface
-p, --protocol        filter by protocol (tcp, udp, icmp)
-o, --output          save logs to file
Example:

bash
Copy
Edit
sudo python sniffer.py -i eth0 -p tcp -o logs.txt
🔒 Disclaimer
This tool is intended for educational and authorized security testing purposes only. Do not use it on networks you do not own or have explicit permission to analyze.

📄 License
MIT License. See LICENSE for more details.
