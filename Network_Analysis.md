# Network Traffic Analysis: DNS Troubleshooting

## Problem Summary
Users reported a "destination port unreachable" error.

## Analysis (tcpdump)
Using `tcpdump`, I identified an **ICMP echo reply** indicating `udp port 53 unreachable`.
- **Conclusion:** The DNS server was down or the firewall was blocking Port 53.
- **Tools used:** `tcpdump`, `ping`, `nslookup`.

## Next Steps
Investigate if the DNS server failure was caused by a misconfiguration or a targeted Denial-of-Service (DoS) attack.
