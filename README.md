<div align="center">

# Networking From Scratch

**A complete, self-paced networking curriculum for cybersecurity beginners.**  
From how a packet moves across a wire to how attackers exploit that movement — built bottom-up, no shortcuts.

![Topics](https://img.shields.io/badge/Topics-37-blue?style=flat-square)
![Level](https://img.shields.io/badge/Level-Beginner%20%E2%86%92%20Advanced-green?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Cybersecurity-red?style=flat-square)

</div>

---

## Why Networking Is the Real Prerequisite

Most beginners jump straight into hacking tools, bug bounties, or cloud certs — and hit a wall fast. That wall is almost always networking.

You can't understand how ARP poisoning works if you don't know what ARP is. You can't debug a firewall rule if you don't know how routing decisions are made. You can't read a Wireshark capture if you've never learned what a TCP handshake looks like.

The pattern is always the same: skip the foundations, get stuck, go back and learn them anyway — except now under pressure, with gaps everywhere.

**This repo is the foundation.** Work through it once, properly, and everything that comes after — CTFs, pentesting, cloud security, DevOps — will make actual sense.

---

## Where Beginners Go Wrong

- **Memorizing without understanding.** Knowing the 7 OSI layers by name is useless. Knowing *why* they exist and what breaks when one fails — that's the skill.
- **Skipping "boring" protocols.** ARP, DHCP, ICMP feel dry until you realize they're the backbone of the most common LAN attacks.
- **Rushing to tools.** Nmap and Wireshark are force multipliers — but only if you already understand what you're looking at. Without the fundamentals, you're just running commands and hoping.
- **No lab practice.** Reading notes without capturing real traffic or scanning a test machine means nothing sticks.

Go slow. The fundamentals compound.

---

## Curriculum

### 🔧 Foundations

| # | Topic | What You'll Learn |
|---|-------|-------------------|
| [01](./01%20-%20Networking%20Fundamentals/01.md) | **Networking Fundamentals** | What networks are, how devices communicate, and the vocabulary used everywhere else in this field |
| [02](./02%20-%20OSI%20Model/02.md) | **OSI Model** | The 7-layer framework — not just the names, but what each layer *actually does* and what breaks when it fails |
| [03](./03%20-%20TCP%20%26%20IP%20Model/03.md) | **TCP/IP Model** | The real-world implementation of networking layers — how the internet is actually built |
| [04](./04%20-%20MAC%20Addresses/04.md) | **MAC Addresses** | Hardware-level addressing, how switches use MACs, and why they matter for local network attacks |
| [05](./05%20-%20IP%20Addressing/05.md) | **IP Addressing** | IPv4/IPv6, address classes, public vs. private IPs, and how every device on the internet gets identified |
| [06](./06%20-%20Subnetting/06.md) | **Subnetting** | Breaking networks into smaller pieces — critical for routing, firewalls, and understanding network design |
| [07](./07%20-%20Ports%20and%20Sockets/07.md) | **Ports and Sockets** | How applications talk over a network, what a socket is, and why port numbers matter for security |

### 📡 Core Protocols

| # | Topic | What You'll Learn |
|---|-------|-------------------|
| [08](./08%20-%20TCP/08.md) | **TCP** | Reliable, connection-oriented transport — handshakes, flow control, and why most traffic uses it |
| [09](./09%20-%20UDP/09.md) | **UDP** | Fast, connectionless alternative — when reliability is traded for speed, and how attackers exploit that |
| [10](./10%20-%20DNS/10.md) | **DNS** | How domain names resolve to IPs — one of the most attacked and misunderstood protocols in existence |
| [11](./11%20-%20DHCP/11.md) | **DHCP** | How devices automatically get IP addresses — and how attackers abuse this process (rogue DHCP) |
| [12](./12%20-%20ARP/12.md) | **ARP** | How IPs map to MACs on a local network — the foundation of layer 2 attacks like ARP poisoning |
| [13](./13%20-%20ICMP/13.md) | **ICMP** | The protocol behind `ping` and `traceroute` — used for diagnostics, recon, and tunneling |
| [14](./14%20-%20HTTP%20%26%20HTTPS/14.md) | **HTTP & HTTPS** | The backbone of the web — request/response cycles, headers, cookies, and what HTTPS actually protects |
| [15](./15%20-%20TLS_SSL%20Fundamentals/15.md) | **TLS/SSL Fundamentals** | How encrypted connections are established — certificates, handshakes, and where things go wrong |

### 🏗️ Network Infrastructure

| # | Topic | What You'll Learn |
|---|-------|-------------------|
| [16](./16%20-%20Routing/16.md) | **Routing** | How packets find their way across networks — routing tables, static vs. dynamic, and common protocols |
| [17](./17%20-%20Switching/17.md) | **Switching** | How traffic moves inside a LAN — MAC tables, broadcast domains, and how switches differ from routers |
| [18](./18%20-%20VLANs/18.md) | **VLANs** | Logically segmenting a network on shared hardware — key for isolation and reducing attack surface |
| [19](./19%20-%20NAT/19.md) | **NAT** | How private IPs reach the public internet — and the security implications of address translation |
| [20](./20%20-%20Proxy%20Servers/20.md) | **Proxy Servers** | Intermediaries between clients and servers — forward, reverse, and transparent proxies explained |
| [21](./21%20-%20Wireless%20Networking/21.md) | **Wireless Networking** | How Wi-Fi works, 802.11 standards, WPA2/WPA3 authentication, and where wireless gets exploited |

### 🔍 Security Tools

| # | Topic | What You'll Learn |
|---|-------|-------------------|
| [22](./22%20-%20Wireshark/22.md) | **Wireshark** | Capturing and analyzing real traffic — the single most important skill for understanding protocols in practice |
| [23](./23%20-%20Nmap/23.md) | **Nmap** | Network scanning and host discovery — mapping what's running, what ports are open, and what OS is in use |
| [24](./24%20-%20Packet%20Sniffing/24.md) | **Packet Sniffing** | Passively capturing traffic, what's visible in plaintext, and why encryption is non-negotiable |

### ⚔️ Attack Techniques

| # | Topic | What You'll Learn |
|---|-------|-------------------|
| [25](./25%20-%20ARP%20Poisoning/25.md) | **ARP Poisoning** | Manipulating ARP caches to redirect traffic — a classic layer 2 attack explained from first principles |
| [26](./26%20-%20DNS%20Spoofing/26.md) | **DNS Spoofing** | Feeding false DNS responses to redirect users — how it works, how to execute it in a lab, how to detect it |
| [27](./27%20-%20Man-in-the-Middle%20Attacks/27.md) | **Man-in-the-Middle Attacks** | Intercepting communication between two parties — combining techniques into a full attack chain |
| [28](./28%20-%20Wi-Fi%20Attacks/28.md) | **Wi-Fi Attacks** | WPA2 handshake cracking, evil twin APs, deauth attacks, and why public Wi-Fi is dangerous |

### 🛡️ Defense & Architecture

| # | Topic | What You'll Learn |
|---|-------|-------------------|
| [29](./29%20-%20Firewalls/29.md) | **Firewalls** | Filtering traffic with rules — stateless vs. stateful, where firewalls sit, and what they can and can't stop |
| [30](./30%20-%20IDS%20%26%20IPS/30.md) | **IDS & IPS** | Detecting and blocking malicious traffic — signatures, anomaly detection, and network placement |
| [31](./31%20-%20VPNs/31.md) | **VPNs** | Encrypted tunnels over public networks — protocols, use cases, and why VPNs aren't magic |
| [32](./32%20-%20Tunneling/32.md) | **Tunneling** | Encapsulating one protocol inside another — used for bypassing filters and maintaining covert access |
| [33](./33%20-%20Pivoting/33.md) | **Pivoting** | Using a compromised machine as a foothold to move laterally through a network |
| [34](./34%20-%20Network%20Segmentation/34.md) | **Network Segmentation** | Dividing a network into zones to contain breaches and limit lateral movement |
| [35](./35%20-%20Zero%20Trust%20Networking/35.md) | **Zero Trust Networking** | The modern security model — never trust, always verify, regardless of network location |
| [36](./36%20-%20Load%20Balancers/36.md) | **Load Balancers** | Distributing traffic across servers — how they work and how they affect visibility and security |
| [37](./37%20-%20Cloud%20Networking%20Basics/37.md) | **Cloud Networking Basics** | How networking concepts translate to cloud — VPCs, security groups, and cloud-native attack surfaces |

---

## Who This Is For

- Complete beginners who want to understand networking properly before touching security tools
- Students preparing for certifications like **CompTIA Network+**, **Security+**, **CEH**, or **OSCP**
- CTF players and ethical hackers who realized their networking foundation has gaps
- Anyone who wants to stop running tools they don't fully understand

---

## ⚠️ Ethical Use

The offensive techniques covered in this repo — ARP poisoning, DNS spoofing, MITM attacks, Wi-Fi attacks — are documented for **educational purposes only**.

Only practice these techniques in your own lab environment or on networks you have explicit, written permission to test. Unauthorized network attacks are illegal in most jurisdictions and carry serious consequences.

---

## Contributing

Found an error, want to expand a topic, or have a better explanation? PRs and issues are welcome.

---

<div align="center">
<sub>Built for anyone serious about understanding networks from the ground up.</sub>
</div>
