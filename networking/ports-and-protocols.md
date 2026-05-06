# Ports and Protocols

Ports and protocols allow devices to communicate across networks.

Protocols define communication rules, while ports identify specific services running on a system.

---

## Common Protocols

| Protocol | Purpose |
|---|---|
| HTTP | Web traffic |
| HTTPS | Secure web traffic |
| FTP | File transfer |
| SSH | Secure remote access |
| DNS | Domain name resolution |
| SMTP | Sending email |

---

## Common Port Numbers

| Port | Service |
|---|---|
| 20/21 | FTP |
| 22 | SSH |
| 25 | SMTP |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |

---

## Important Networking Commands

### `ping`

Tests network connectivity.

```bash
ping google.com
```

---

### `netstat`

Displays active network connections.

```bash
netstat
```

---

### `ifconfig`

Displays network interface information.

```bash
ifconfig
```

---

### `ssh`

Connects securely to remote systems.

```bash
ssh user@host
```

---

## Why Ports Matter in Cybersecurity

Open ports can create security risks if services are vulnerable or misconfigured.

Cybersecurity professionals use tools like:
- Nmap
- Wireshark
- Netstat

to monitor and analyze network activity.
