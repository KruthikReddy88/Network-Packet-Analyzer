# Packet Sniffer Tool

## Overview

This repository contains a simple packet sniffer tool developed in C that captures and analyzes network packets. The tool extracts and displays relevant information such as source and destination IP addresses, protocols (TCP/UDP), and payload data. This tool is intended for educational purposes and should be used ethically.

## Features

- Captures live network packets from the selected network interface.
- Displays source and destination IP addresses.
- Identifies and displays the protocol (TCP/UDP) used.
- Extracts and prints source and destination ports for TCP and UDP packets.
- Displays raw payload data of captured packets.

## Requirements

- C compiler (GCC recommended)
- `libpcap` library

## Ethical Use

This tool is intended for educational purposes. Ensure you have permission to monitor the network you are capturing packets from. Unauthorized use of packet sniffing tools can lead to legal consequences.

## Code Explanation

- **`packet_handler` function**: Callback function that processes each captured packet, extracting IP addresses, protocols, and payload data.
- **`main` function**: Initializes the packet capture, finds a network device, and starts the capturing loop.

## Example Output

The tool displays captured packet details, including source and destination IP addresses, protocol information, and raw payload data.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Contributions

Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and improvements are welcome!
