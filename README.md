# Wireshark-Packet-Analysis
Practical guide to network traffic analysis and Wireshark display filters
# 🦈 Wireshark & Packet Analysis Cheatsheet

A practical guide to network traffic analysis, basic display filters, and protocol inspection using Wireshark.

Essential Wireshark Display Filters

Filter by IP Address |     `ip.addr == 192.168.1.1` 
Filter by Source IP |      `ip.src == 192.168.1.5` 
Filter by Destination IP|  `ip.dst == 10.0.0.1` 
Filter by HTTP Traffic |   `http` 
Filter HTTP GET Requests | `http.request.method == "GET"` 
Filter DNS Requests |      `dns` 
Filter by TCP Port |       `tcp.port == 443` 
Exclude Protocol |        `!arp` or `not arp` 


ractical Workflow
1. **Capture Traffic:** Select active Network Interface (e.g., `eth0` or `wlan0`) and start capture.
2. **Apply Filters:** Isolate target traffic using Display Filters.
3. **Follow Stream:** Right-click on a TCP/HTTP packet -> **Follow** -> **TCP Stream** to view plain-text data.

---
*Created by Yasidu Sandaruwan | Cybersecurity Enthusiast*
