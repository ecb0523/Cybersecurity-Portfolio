# Incident Report: SYN Flood Attack Analysis

## Incident Summary
The organization experienced a network interruption where the website timed out. Analysis of the logs revealed a massive influx of TCP SYN requests from an unfamiliar IP address.

## Technical Analysis
The attack exploited the **TCP Three-Way Handshake**:
1. **SYN:** Malicious actor sends a flood of SYN packets.
2. **SYN-ACK:** The server responds and allocates resources for the connection.
3. **ACK:** The attacker never sends the final ACK, leaving the server’s backlog full and unable to process legitimate users.

## Remediation Recommendations
- Implement a **Firewall** with rate-limiting rules.
- Deploy an **Intrusion Detection System (IDS)** to alert on abnormal SYN traffic patterns.
- Enable **SYN Cookies** on the server to prevent resource exhaustion.
