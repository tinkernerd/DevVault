---
title: Networking Resources
created_at: 2025-02-16T20:24:23-05:00
modified_at: 2025-02-16T20:31:18-05:00
category: Info Tech
type: Dashboard
topic:
  - Networking
status: Active
---
# Networking Notes
```dataview  
TABLE WITHOUT ID
link(file.path, title) AS "Note", type AS "Type", created_at AS "Date Created", file.mtime AS "Last Modified", status AS "Status"
FROM "Notes"
WHERE contains(topic, "Networking")
SORT title ASC
````



## 🛠️ Quick Access

For frequently used networking tools, cheat sheets, and diagnostic commands.

### 🖧 IP & Subnetting Tools

- **Subnet Calculator** - [Online Tool](https://www.subnet-calculator.com/)
- **IPv6 Subnetting** - [IPv6 CIDR Calculator](https://www.ultratools.com/tools/ipv6CIDRToRange)
- **DNS Lookup** - [MXToolbox](https://mxtoolbox.com/)
- **Whois Lookup** - [Whois Domain Lookup](https://who.is/)
- **BGP Routing Info** - [Hurricane Electric BGP Tool](https://bgp.he.net/)

### 🔍 Common Network Troubleshooting Commands

|Command|Description|
|---|---|
|`ping 8.8.8.8`|Checks basic connectivity to a remote host.|
|`tracert google.com` (Windows) / `traceroute google.com` (Linux)|Traces the route packets take to a destination.|
|`ipconfig /all` (Windows) / `ifconfig` or `ip addr` (Linux)|Displays IP and network adapter details.|
|`nslookup example.com`|Performs DNS resolution lookup.|
|`netstat -ano`|Lists active network connections and ports.|
|`tcpdump -i eth0`|Captures network traffic on an interface.|

---

## ⚡ Networking Basics & Cheat Sheet

### 🔌 TCP/IP Model vs. OSI Model

|Layer|OSI Model|TCP/IP Model|Example Protocols|
|---|---|---|---|
|7️⃣|Application|Application|HTTP, FTP, SMTP|
|6️⃣|Presentation|🟢 Combined|TLS, SSL|
|5️⃣|Session|🟢 Combined|SSH, NetBIOS|
|4️⃣|Transport|Transport|TCP, UDP|
|3️⃣|Network|Internet|IP, ICMP, BGP|
|2️⃣|Data Link|Network Access|Ethernet, ARP|
|1️⃣|Physical|Network Access|Cables, Wi-Fi|

---

## 🌍 Network Security Best Practices

1. **Use Strong Passwords** – Default router passwords should be changed immediately.
2. **Enable Firewalls** – Use both hardware and software firewalls for security.
3. **Implement VLANs** – Segment networks to isolate sensitive devices.
4. **Disable Unused Ports** – Close unnecessary ports to minimize attack surfaces.
5. **Monitor Traffic** – Use **Wireshark**, **NetFlow**, or **IDS/IPS** systems to analyze suspicious behavior.
6. **Keep Firmware Updated** – Regularly update routers, switches, and firewalls.

---

## 🔧 Network Protocols & Port Numbers

|Protocol|Port|Description|
|---|---|---|
|**HTTP**|80|Web traffic (unsecured)|
|**HTTPS**|443|Secure web traffic|
|**DNS**|53|Domain Name System|
|**SSH**|22|Secure Shell remote access|
|**FTP**|21|File Transfer Protocol|
|**SMTP**|25|Email sending|
|**IMAP**|143|Email retrieval|
|**RDP**|3389|Remote Desktop Protocol|

---

## 📊 Network Performance Monitoring

For keeping an eye on your network's health.

|Tool|Function|
|---|---|
|**Nagios**|Network monitoring & alerting|
|**Zabbix**|Server & network monitoring|
|**Grafana**|Visualizing network performance metrics|
|**SolarWinds**|Enterprise-grade network monitoring|
|**Smokeping**|Latency monitoring & graphing|

---

🚀 **Need More?** Browse the Networking Notes or start a new note for troubleshooting and configurations.

---
