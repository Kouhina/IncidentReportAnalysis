# IncidentReportAnalysis
NIST Cyber Security Framework

Summary: I was working for multimedia company and discover a DDOS attack and tooks the 2 hours to recover. Atcually there was flood of ICMP packets so server gets down of our multimadia company.
Incident Management team responded as blocking of ICMP packets.

Identify: The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

Protect: To address this security event, the network security team implemented: 
1)A new firewall rule to limit the rate of incoming ICMP packets.
2)Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets.
3)Network monitoring software to detect abnormal traffic patterns.
4)An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

Detect: Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Respond: For future security events, the cybersecurity team will isolate affected systems
to prevent further disruption to the network. They will attempt to restore any

critical systems and services that were disrupted by the event. Then, the team
will analyze network logs to check for suspicious and abnormal activity. The
team will also report all incidents to upper management and appropriate legal
authorities, if applicable.

Recover : To recover from a DDoS attack by ICMP flooding, access to network services
need to be restored to a normal functioning state. In the future, external ICMP
flood attacks can be blocked at the firewall. Then, all non-critical network
services should be stopped to reduce internal network traffic. Next, critical
network services should be restored first. Finally, once the flood of ICMP
packets have timed out, all non-critical network systems and services can be
brought back online.
