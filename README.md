# Wi-Fi Cracking Automation

This repository contains a Python script that automates several Wi-Fi cracking tasks, including:

* Starting and stopping monitor mode
* Scanning for Wi-Fi networks
* Getting a handshake from a target network
* Installing the necessary tools for Wi-Fi cracking
* Cracking a handshake using a wordlist or without a wordlist
* Creating a custom wordlist
* Performing WPS attacks on a network

The script was developed using Python 3 and has been tested on Linux systems. Some of the tools that the script uses, such as Aircrack-ng, Crunch, and Reaver, need to be installed on the system prior to running the script.

## Installation

To use this script, clone this repository to your local machine:

<pre><div class="p-4 overflow-y-auto"><code  style="color:white" class="!whitespace-pre hljs language-bash">git clone https://github.com/V31l0x1/wifi-cracking-automation.git
</code></div></div></pre>

Then, install the required tools by running the following command in the repository directory:

<pre><div class="p-4 overflow-y-auto"><code style="color:white" class="!whitespace-pre hljs language-bash">sudo python install -r requirements.txt
</code></div></div></pre>

## Usage

To use the script, navigate to the repository directory and run the `wifi-crack.py` file:

<pre><div class="p-4 overflow-y-auto"><code  style="color:white" class="!whitespace-pre hljs">python wifi-crack.py
</code></div></div></pre>

The script will display a menu with several options. Choose the desired option by entering the corresponding number and following the prompts.

Note that some of the options require a wireless interface name, a BSSID, a channel number, a path to an output file, or a number of packets. Make sure to provide the correct information when prompted.

## Disclaimer

This script is intended for educational and ethical purposes only. Using this script to attack wireless networks without permission is illegal and unethical. The author of this script is not responsible for any misuse or damage caused by this script. Use at your own risk.

## Credits

This script was created by V31L_0x1. Some of the tools used by the script were developed by other authors and are credited in the script comments.

## License

This script is licensed under the MIT License. See the LICENSE file for details.
