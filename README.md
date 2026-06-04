# Cybersecurity-Task4
# Task 4 - Setup and Use a Firewall on Windows

## Objective
Configure and test basic firewall rules to allow or block network traffic using Windows Defender Firewall.

## Tool Used
- Windows Defender Firewall with Advanced Security

## Steps Performed

1. Opened Windows Defender Firewall with Advanced Security.
2. Navigated to Inbound Rules.
3. Created a new inbound rule.
4. Selected Port as the rule type.
5. Chose TCP and specified Port 23 (Telnet).
6. Selected "Block the Connection".
7. Applied the rule to all profiles (Domain, Private, and Public).
8. Named the rule "Block Telnet Port 23".
9. Verified that the rule was successfully created.
10. Captured screenshots of the firewall rule.
11. Removed the rule to restore the original firewall configuration.

## Screenshots
- Screenshot 1: Firewall rule created (Block Telnet Port 23)
- Screenshot 2: Firewall rule deleted/restored

## Outcome
Successfully learned how to create, manage, and remove firewall rules using Windows Defender Firewall. Also understood how firewalls filter network traffic and improve system security.

## Key Concepts
- Firewall Configuration
- Network Traffic Filtering
- Inbound Rules
- Ports
- Telnet (Port 23)
- Windows Defender Firewall

## Interview Questions and Answers

### 1. What is a firewall?
A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined security rules.

### 2. Difference between Stateful and Stateless Firewall?
Stateful firewalls track active connections and make decisions based on connection state, while stateless firewalls inspect each packet independently.

### 3. What are inbound and outbound rules?
Inbound rules control incoming network traffic, while outbound rules control outgoing network traffic.

### 4. How does UFW simplify firewall management?
UFW (Uncomplicated Firewall) provides simple commands for managing firewall rules in Linux.

### 5. Why block Port 23 (Telnet)?
Port 23 is used by Telnet, which sends data without encryption. Blocking it helps improve security.

### 6. What are common firewall mistakes?
- Leaving unnecessary ports open
- Using weak rules
- Not reviewing firewall settings regularly

### 7. How does a firewall improve network security?
A firewall prevents unauthorized access, blocks malicious traffic, and protects systems from network attacks.

### 8. What is NAT in firewalls?
Network Address Translation (NAT) hides internal IP addresses behind a public IP address, improving security and conserving IP addresses.

## Conclusion
This task provided practical experience in configuring firewall rules and understanding how firewalls protect systems by controlling network traffic.
