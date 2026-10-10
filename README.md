# 🛡️ 30 Days of Cybersecurity Learning

## About This Project
I am documenting my cybersecurity learning journey through Linux security, system investigation, network fundamentals, and packet analysis.

## Learning Progress

### Day 5 — Linux Security Investigation
- Studied Linux security investigation concepts.
- Completed a knowledge quiz.

### Day 6 — Linux Permissions
- Studied Linux file permissions and access control.
- Completed a knowledge quiz.

### Day 7 — Wireshark and TShark
- Learned the purpose of Wireshark and packet analysis.
- Understood Packet List, Packet Details, and Packet Bytes.
- Installed TShark in Ubuntu on WSL.
- Verified the installation with `tshark --version`.
- Listed capture interfaces with `tshark -D`.
- Learned about DNS and TCP display filters.

### Day 8 — Network Fundamentals
- Learned TCP versus UDP.
- Studied common ports: SSH (22), DNS (53), HTTP (80), and HTTPS (443).
- Learned about IP addresses, listening sockets, and DNS.
- Studied network troubleshooting commands.

## Tools
- Ubuntu on WSL
- Linux command line
- Wireshark
- TShark
- GitHub

## Commands

```bash
tshark --version
tshark -D
ip addr
ss -tuln
ss -tn
getent hosts example.com
curl -I --max-time 10 https://example.com
```

## Next Steps
- Complete network troubleshooting exercises.
- Analyze a sample PCAP or PCAPNG file.
- Identify source and destination IP addresses.
- Practice DNS and TCP packet filtering.
- Continue the 30-day learning plan.

## Ethical Use
All exercises are for educational and defensive cybersecurity purposes. Analyze only systems and traffic you are authorized to inspect.

**Note:** Practical results will be documented after completing and verifying each exercise.
