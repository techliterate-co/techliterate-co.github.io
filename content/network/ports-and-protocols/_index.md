+++
date = '2025-09-25T14:05:30-06:00'
title = 'Ports and Protocols'
weight = 10

[params]
  menuPre = '<i class="fa-solid fa-handshake"></i> '
+++

### Ports & Protocols

When data moves across a network, it doesn’t just travel aimlessly. Every piece
of software that communicates over the internet uses a **protocol** (a set of
rules for how to talk) and a **port** (like a numbered door that traffic goes
through on a computer). The Internet Protocol (IP) is responsible for moving
packets between devices, while higher-level protocols like TCP (Transmission
Control Protocol) and UDP (User Datagram Protocol) decide how those packets are
organized and delivered.

**TCP** is like registered mail: every packet is tracked, confirmed, and
re-sent if it goes missing. It’s slower but reliable—perfect for web pages,
email, or file transfers where accuracy matters. **UDP**, on the other hand, is
like a postcard tossed in the wind: it gets there faster, but with no
guarantees. That’s fine for live video, voice calls, or online gaming, where
speed matters more than perfection.

A **port number** tells your device which application should handle incoming
data. For example, web browsers use port 80 for HTTP and port 443 for HTTPS,
while email clients might connect on ports 25, 143, or 587 depending on the
service. Firewalls, VPNs, and many security tools work by watching or blocking
traffic on specific ports. Understanding ports helps you see why services run
the way they do—and how attackers sometimes look for weak points.

---

### Common TCP/IP Ports and Protocols

| Port | Protocol          | Typical Use |
|------|-------------------|-------------|
| 20   | FTP (Data)        | File Transfer Protocol (data channel) |
| 21   | FTP (Control)     | File Transfer Protocol (commands) |
| 22   | SSH               | Secure Shell (remote login, file transfer via SCP/SFTP) |
| 23   | Telnet            | Unencrypted remote login (legacy, insecure) |
| 25   | SMTP              | Simple Mail Transfer Protocol (email sending) |
| 53   | DNS               | Domain Name System (queries and responses) |
| 67   | DHCP Server       | Dynamic Host Configuration Protocol (server to client) |
| 68   | DHCP Client       | Dynamic Host Configuration Protocol (client to server) |
| 69   | TFTP              | Trivial File Transfer Protocol (lightweight, no auth) |
| 80   | HTTP              | Web traffic (unencrypted) |
| 110  | POP3              | Post Office Protocol v3 (email retrieval) |
| 123  | NTP               | Network Time Protocol (clock synchronization) |
| 143  | IMAP              | Internet Message Access Protocol (email retrieval) |
| 161  | SNMP              | Simple Network Management Protocol (monitoring devices) |
| 389  | LDAP              | Lightweight Directory Access Protocol (directory services) |
| 443  | HTTPS             | Secure web traffic (encrypted with TLS/SSL) |
| 445  | SMB               | Server Message Block (file/printer sharing, Windows) |
| 514  | Syslog            | System logging |
| 587  | SMTP (Submission) | Secure mail submission |
| 3389 | RDP               | Remote Desktop Protocol (Windows remote access) |

---

