# 🕵️‍♂️ Wireshark - Network Traffic Analyzer

**Wireshark** is a powerful open-source tool for capturing and analyzing network packets in real time. It’s used by cybersecurity professionals, network admins, and penetration testers to inspect network protocol details and troubleshoot issues.

---

## 🚀 Quick Start

1. **Install** from [https://www.wireshark.org](https://www.wireshark.org)
2. **Run** with admin/root privileges
3. **Choose** your active network interface
4. **Start** capturing live traffic
5. **Apply filters** to focus (e.g. `http`, `dns`, `ip.addr == 192.168.1.1`)
6. **Stop capture** and analyze packets
7. **Save** as `.pcap` for future use

---

## 🔧 Features

- Live network capture from interfaces
- Protocol-level packet analysis
- Advanced filtering capabilities
- Export/import `.pcap` files
- Color-coded traffic visualization

---

## 🔍 Example Filters

| Filter              | Purpose                       |
|---------------------|-------------------------------|
| `http`              | Show HTTP packets             |
| `dns`               | Show DNS queries/responses    |
| `tcp.flags.syn == 1`| Detect SYN scans              |
| `ip.addr == x.x.x.x`| Filter by IP address          |

---

## 📁 Output

Captured traffic is saved as `.pcap` files and can be shared or revisited for detailed inspection.

---

## 📎 License
