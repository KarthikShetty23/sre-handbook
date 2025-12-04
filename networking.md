# Networking Fundamentals

## Protocols & Transport Layer 
| Protocol | Full Name | Description | SRE use Case |
| :--- | :--- | :--- | :--- |
| **IP** | Internet Protocol | The addressing System for the Internet. Delivers packets from source to destination.| The "Postal Service" of the web |
| **TCP** | Transmission Control Protocol | **Reliable**, connection-oriented. Guarantees data arrives in order. Retransmits lost packets. | Web browsing (HTTP), Emails, File transfers |
| **UDP** | User Datagram Protocol | **Fast**, connection-less. "Fire and Forgot. No guarantee of delivery . | Streaming, gaming, DNS lookups |


## Adressing ( The ID cards)
| Type | Format Example | Notes |
| :--- | :--- | :--- |
| **IPv4** | `192.168.1.1` | 32-bit address. Split into 4 "octets"(0-255). Running out of Address Globally.|
| **IPv6** | `2001:0db8::` | 128- bit address. Uses Hexadecimal. Created to solve IPv4 shortage |
| **Subnet Mask** |  `255.255.255.0` | Defines how small or large the network is. Tells the computer " who is my neighbour?" vs "who is on the internet?" |

## Hardware 
* **Switch:** Connects the devices within the *same* network (LAN). Uses MAC address.
* **Router:** Connects *different* networks together (WAN). Uses IP address 
 
