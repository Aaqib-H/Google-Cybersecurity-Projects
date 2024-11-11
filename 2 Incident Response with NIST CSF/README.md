# Incident Response with NIST CSF

## Project Description
This project simulates the role of a cybersecurity analyst documenting an incident report following a network attack. The report is based on a scenario where a multimedia company experienced a DDoS (Distributed Denial of Service) attack. The incident involved a flood of ICMP packets disrupting network operations, requiring immediate response actions to restore normal network functionality. This project demonstrates how to apply the **NIST Cybersecurity Framework (CSF)** to improve response capabilities and bolster future incident detection and prevention.

## Tools Used
- **NIST CSF**: Cyber Security Framework
- **Incident Response Plan**: A structured approach to document and respond to the incident.

## Skills Learned
- Applying NIST CSF to real-world incident response
- Documenting incident reports for enhanced communication and transparency
  
## Scenario
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets
- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
- Network monitoring software to detect abnormal traffic patterns
- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. 

## NIST Cybersecurity Framework (CSF) Steps
This report follows the five functions of the NIST CSF: Identify, Protect, Detect, Respond, and Recover.

### 1. **Identify**
   - **Goal**: Regularly audit internal networks, systems, devices, and access privileges to pinpoint security gaps.
   - **Action**: Conducted a comprehensive audit to catalog assets and identify unprotected network entry points, specifically unfiltered ICMP traffic.

### 2. **Protect**
   - **Goal**: Secure internal assets through updated policies, procedures, and technical measures.
   - **Action**: Implemented firewall rules to limit incoming ICMP traffic, established source IP verification to counteract IP spoofing, and enhanced training for the incident response team.

### 3. **Detect**
   - **Goal**: Improve monitoring and detection capabilities to quickly identify security incidents.
   - **Action**: Deployed network monitoring software to detect abnormal traffic patterns and installed IDS/IPS systems to screen ICMP packets with suspicious traits.

### 4. **Respond**
   - **Goal**: Swiftly contain, analyze, and neutralize security incidents.
   - **Action**: Blocked incoming ICMP traffic, suspended non-critical network services, restored essential services, and documented incident response procedures.

### 5. **Recover**
   - **Goal**: Restore systems to normal operation and reinforce protections.
   - **Action**: Fully restored network functionality, updated firewall configurations, and adjusted network policies to prevent similar attacks.

## Documentation
![Incident Response Analysis](https://github.com/user-attachments/assets/fc43f043-bfb5-4cba-9118-31d125df3d1e)



## Project Outcome
This project highlighted the importance of structured incident response and post-incident improvements. By following the NIST CSF, the company strengthened its network defenses, improved monitoring systems, and reduced vulnerabilities against future attacks.
