# DNS Basics

DNS (Domain Name System) translates domain names into IP addresses so devices can locate websites and services on a network.

Example:
- `google.com` → `142.250.x.x`

Without DNS, users would need to remember IP addresses instead of domain names.

---

## How DNS Works

1. A user enters a website name into a browser
2. DNS searches for the matching IP address
3. The browser connects to the correct server
4. The website loads

---

## Common DNS Terms

### Domain Name
Human-readable website name.

Example:

```text
google.com
```

---

### IP Address
Numeric address used to identify devices on a network.

Example:

```text
192.168.1.1
```

---

### DNS Server
A server responsible for translating domain names into IP addresses.

---

## Useful Commands

### `nslookup`

Look up DNS information.

```bash
nslookup google.com
```

---

### `ping`

Test connectivity to a domain or IP address.

```bash
ping google.com
```

---

### `dig`

Query DNS records.

```bash
dig google.com
```

---

## Why DNS Matters in Cybersecurity

DNS is important in cybersecurity because attackers may:
- create malicious domains,
- redirect users to fake websites,
- or use DNS for command-and-control traffic.

Security analysts monitor DNS traffic to identify suspicious activity.
