# 🌐 Networking From Scratch

Most beginners jump straight into hacking tools, CTFs, or cloud certifications — and hit a wall fast. That wall is almost always **networking**. You can't understand how attacks work if you don't know what a packet is. You can't debug infrastructure if you don't know what DNS does. You can't secure what you don't understand.

This repo exists to fix that. No shortcuts, no hand-waving — just networking built up properly, concept by concept.

---

## Why Beginners Fail

The most common mistake is treating networking as a checkbox. People memorize the OSI model layers for an exam and move on, never actually understanding *why* data gets encapsulated, or what happens at each hop. Then they get stuck the moment something breaks in the real world.

The second mistake is skipping the boring stuff — subnetting, ARP, ICMP — because it doesn't feel exciting. But these are exactly the foundations that make attack techniques and defense strategies click later. If you don't know how ARP works, ARP poisoning is just a magic trick. If you know it deeply, you understand why it works and how to detect it.

Go slow. The fundamentals compound.

---

## 📖 Chapters

| # | Chapter | What You'll Learn |
|---|---------|-------------------|
| 01 | **Networking Fundamentals** | What a network is, how devices communicate, and the vocabulary you'll use everywhere else |
| 02 | **OSI Model** | The 7-layer framework for understanding how data travels — not just names, but what each layer actually does |
| 03 | **TCP/IP Model** | The real-world implementation of the OSI model, and how the internet is actually built |
| 04 | **MAC Addresses** | Hardware-level addressing, how switches use MACs, and why they matter for local network attacks |
| 05 | **IP Addressing** | IPv4/IPv6, address classes, public vs private IPs, and how every device on the internet gets identified |
| 06 | **Subnetting** | Breaking networks into smaller pieces — critical for routing, firewalls, and network design |
| 07 | **Ports and Sockets** | How applications talk over a network, what a socket is, and why port numbers matter for security |
| 08 | **TCP** | The reliable, connection-oriented protocol — handshakes, flow control, and why it's used for most traffic |
| 09 | **UDP** | The fast, connectionless alternative — when reliability is traded for speed |
| 10 | **DNS** | How domain names resolve to IPs — one of the most attacked and misunderstood protocols |
| 11 | **DHCP** | How devices automatically get IP addresses — and how attackers can abuse this process |
| 12 | **ARP** | How IPs map to MAC addresses on a local network — the foundation of layer 2 attacks |
| 13 | **ICMP** | The protocol behind `ping` and `traceroute` — used for diagnostics and recon |
| 14 | **HTTP & HTTPS** | The backbone of the web, request/response cycles, headers, and what TLS actually protects |
| 15 | **TLS/SSL Fundamentals** | How encrypted connections are established — certificates, handshakes, and common weaknesses |
| 16 | **Routing** | How packets find their way across networks — static routes, dynamic protocols, and routing tables |
| 17 | **Switching** | How traffic moves inside a local network, MAC tables, and how switches differ from routers |
| 18 | **VLANs** | Logically segmenting a network on shared physical hardware — key for network isolation |
| 19 | **NAT** | How private IPs reach the public internet — and the security implications of address translation |
| 20 | **Proxy Servers** | Intermediaries between clients and servers — how they work, and why they're used for privacy and filtering |
| 21 | **Wireless Networking** | How Wi-Fi works, 802.11 standards, authentication modes, and common wireless weaknesses |
| 22 | **Wireshark** | Capturing and analyzing real network traffic — the most important skill for understanding protocols hands-on |
| 23 | **Nmap** | Network scanning and host discovery — the go-to tool for mapping what's running on a network |
| 24 | **Packet Sniffing** | Passively capturing traffic, what's visible in plaintext, and why encryption matters |
| 25 | **ARP Poisoning** | Manipulating ARP tables to redirect traffic — a classic layer 2 attack explained from the ground up |
| 26 | **DNS Spoofing** | Feeding false DNS responses to redirect users — how it works and how to detect it |
| 27 | **Man-in-the-Middle Attacks** | Intercepting communication between two parties — combining multiple techniques into a full attack chain |
| 28 | **Wi-Fi Attacks** | WPA2 cracking, evil twin APs, deauth attacks, and why public Wi-Fi is risky |
| 29 | **Firewalls** | Filtering traffic with rules — stateless vs stateful, where firewalls sit, and what they can and can't stop |
| 30 | **IDS & IPS** | Detecting and blocking malicious traffic — signatures, anomaly detection, and placement in a network |
| 31 | **VPNs** | Encrypted tunnels over public networks — how they work, protocols used, and their limitations |
| 32 | **Tunneling** | Encapsulating one protocol inside another — used for bypassing filters and maintaining access |
| 33 | **Pivoting** | Using a compromised machine as a foothold to reach deeper into a network |
| 34 | **Network Segmentation** | Dividing a network into zones to limit the blast radius of a breach |
| 35 | **Zero Trust Networking** | The modern security model — never trust, always verify, regardless of network location |
| 36 | **Load Balancers** | Distributing traffic across multiple servers — how they work and how they affect security |
| 37 | **Cloud Networking Basics** | How networking concepts translate to AWS/Azure/GCP — VPCs, security groups, and cloud-specific attacks |

---

> ⚠️ The offensive techniques in this repo (ARP poisoning, DNS spoofing, MITM, Wi-Fi attacks) are for educational purposes only. Practice in a lab environment or on networks you have explicit permission to test. Unauthorized attacks are illegal.
