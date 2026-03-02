# Cybersecurity-Incident-Report-Network-Traffic-Analysis
Incident report analyzing an ICMP‑based DoS attack using the NIST Cybersecurity Framework. Includes root‑cause analysis, firewall misconfiguration findings, and recommended improvements such as ICMP rate‑limiting, monitoring, and IDS/IPS controls.
Cybersecurity-Incident-Report-Network-Traffic-Analysis

Incident report analyzing an ICMP‑based DoS attack using the NIST Cybersecurity Framework. Includes root‑cause analysis, firewall misconfiguration findings, and recommended improvements such as ICMP rate‑limiting, monitoring, and IDS/IPS controls.
📘 Project Overview

This project documents a simulated network security incident involving an ICMP‑based Denial of Service (DoS) attack that disrupted a multimedia company’s internal network for two hours. The report applies the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF) to analyze the event, identify vulnerabilities, and recommend improvements to strengthen the organization’s security posture.
🧭 Scenario Summary

    A malicious actor launched a flood of ICMP packets into the company’s network.

    An unconfigured firewall allowed unrestricted ICMP traffic, overwhelming internal services.

    Network resources became unavailable, halting normal operations.

    The incident response team blocked incoming ICMP packets, shut down non‑critical services, and restored essential systems.

🛡 NIST CSF Analysis
Identify

    Unconfigured firewall allowed unrestricted ICMP traffic.

    Lack of regular audits contributed to unnoticed vulnerabilities.

    Business operations were impacted due to network service outages.

Protect

    Missing firewall rules and insufficient access controls.

    Need for stronger network policies and baseline configurations.

    Lack of preventative monitoring tools.

Detect

    ICMP flood detected only after services became unresponsive.

    Limited visibility into abnormal traffic patterns.

    Monitoring tools needed to detect anomalies earlier.

Respond

    Blocked incoming ICMP packets to contain the attack.

    Disabled non‑critical services to stabilize the network.

    Coordinated response restored critical operations.

Recover

    Restored internal network services to normal operation.

    Implemented long‑term improvements to prevent recurrence.

    Documented lessons learned to strengthen future response efforts.

🔧 Security Improvements Implemented

    ICMP rate‑limiting firewall rule

    Source IP address verification

    Network monitoring software for anomaly detection

    IDS/IPS filtering for suspicious ICMP traffic

🧠 Skills Demonstrated

    Incident response and documentation

    Network security fundamentals

    NIST CSF application

    Root‑cause analysis

    Understanding of DoS attack behavior

📸 Screenshot

![Incident Report Screenshot](screenshot.png)
📚 Lessons Learned

This incident highlights the importance of proactive firewall configuration, continuous monitoring, and structured response planning. Applying the NIST CSF provides a clear framework for identifying weaknesses, improving defenses, and strengthening overall network resilience
