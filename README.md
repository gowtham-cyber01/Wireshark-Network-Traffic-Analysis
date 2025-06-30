# 📦 Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
Capture live network packets and identify basic protocols and traffic types.

## 🛠 Tools
- Wireshark (free)

---

## 📋 Steps Performed

1. Installed Wireshark.
2. Started capturing on the active network interface.
3. Browsed websites and/or used `ping` command to generate network traffic.
4. Stopped the capture after around one minute.
5. Filtered captured packets by protocol to analyze specific traffic.
6. Identified multiple protocols in the capture.
7. Exported the capture file as `task5_capture.pcapng`.

---

## 📊 Protocols Identified & Explanation

| Protocol | Purpose |
|---------|---------|
| TCP | Transport layer protocol used for reliable data transfer between devices. Carries most internet traffic including web browsing, emails, file transfers, etc. |
| SSL v2 | Secure Sockets Layer version 2 – an older encryption protocol used to secure network communications. SSL v2 is outdated and insecure, replaced by modern protocols like TLS 1.2 and TLS 1.3. |

---

## 📝 Summary of Findings

- Successfully captured live network packets.
- Observed TCP traffic showing the underlying transport connections.
- Identified SSL v2 packets indicating encrypted communication attempts.
- Learned how to filter, analyze, and understand basic protocols using Wireshark.

---

## ✅ Deliverables

- Packet capture file: `task5_capture.pcapng`
- This README report

---

## 🚀 Outcome

- Hands-on experience using Wireshark.
- Practical understanding of capturing and analyzing network traffic.
- Improved awareness of basic network protocols and encryption.
