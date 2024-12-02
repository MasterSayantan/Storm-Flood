# Storm Flood Tool

## What is Storm Flood Tool?

The **Storm Flood Tool** is a DDoS (Distributed Denial of Service) attack tool that allows you to stress test networks or servers by sending massive amounts of UDP packets to a target. This type of attack can simulate real-world DDoS scenarios where a target system is overwhelmed by traffic, leading to service disruption.

**Disclaimer:** This tool is strictly for educational purposes and should only be used in environments where you have explicit permission to conduct stress testing. Misuse of this tool, such as attacking systems without permission, is illegal and could result in serious consequences. The author is not responsible for any misuse of this tool.

---

## How Does it Work?

The **Storm Flood Tool** operates by sending random UDP packets to a specified IP address or domain name. The user can choose to send these packets either through all available ports or target a specific port. Each packet is randomly generated and can be as large as 1490 bytes.

### Key Features:
- **DDoS Simulation:** Mimics large-scale traffic by flooding the target with UDP packets.
- **Target IP or Domain:** Can attack a direct IP address or resolve a domain name to its corresponding IP.
- **Customizable Port Attack:** You can choose to attack either all ports or a specific port.
- **Real-time Packet Count:** Displays a real-time count of packets sent to the target.

### How It Works:
1. **IP or Domain Resolution:** The tool can target a domain, resolving it to an IP address, or directly attack a specific IP.
2. **Port Selection:** Users can choose whether to attack all ports or focus on a single port.
3. **Flood Execution:** The tool sends UDP packets continuously, displaying the number of packets sent to the target along with the port number.

![image](https://github.com/MasterSayantan/Storm_Flood/blob/main/picture.png)

---


## Installation Requirements

To run the Storm Flood tool, ensure you have Python 3.x installed along with the following libraries:

- `tqdm.auto`:This module provides a progress bar and needs to be installed.

## Installation Steps

1. **Clone this repository**:
   ```bash
   git clone https://github.com/MasterSayantan/Storm_Flood.git
   cd Storm_Flood
   pip install -r requirements.txt
   python3 Storm_Flood.py
   ```

 ## Usage
1. Select an Option: The tool will present a menu where you can choose to attack a domain or an IP address:

       Choose Domain and enter the domain name to resolve it to an IP address.
       Choose IP Address and enter the IP directly.
2. Port Selection: After providing the IP or domain, the tool will ask if you want to attack a specific port or all ports:

       Select Y for a specific port.
       Select N to attack all ports.
3. Packet Flooding: Once the attack starts, the tool will continuously send UDP packets and display the number of packets sent along with the target's IP and port.

## Legal Disclaimer
  The Storm Flood Tool is intended for educational purposes only and should only be used on systems where you have explicit permission to conduct testing. Unauthorized usage of this tool is illegal and can lead to severe consequences. The author is not responsible for any misuse or damage caused by this tool.
