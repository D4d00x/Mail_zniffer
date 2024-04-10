# Mail Sniffer

Mail Sniffer is a Python script that uses Kamene library for packet sniffing to capture emails transmitted over unencrypted protocols (such as POP3, SMTP, and IMAP) on a network.

## Prerequisites

- Python 3.x
- Kamene library (`pip install kamene`)

## Usage

1. Clone the repository:

git clone https://github.com/your-username/mail-sniffer.git

2. Navigate to the project directory:

cd mail-sniffer

3. Run the script:

python mail_sniffer.py

4. The script will start sniffing packets on specified TCP ports (110, 25, and 143) and print out any packets containing keywords 'user' or 'pass', indicating potential email credentials.

## Disclaimer

This script is intended for educational purposes and should only be used on networks where you have explicit permission to monitor traffic. Unauthorized monitoring of network traffic is illegal and unethical.

Author: Dado Hatipovic
