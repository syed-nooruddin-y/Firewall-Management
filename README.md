# Firewall-Management
Firewall implementation in LINUX


##Introduction

In this task, I configured and tested firewall rules on Kali Linux using UFW (Uncomplicated Firewall).
The goal was to understand how firewall rules filter network traffic by allowing or blocking specific ports.

This task is important because firewalls are one of the fundamental layers of system security.
Learning how to manage firewall rules helps secure systems and prevent unauthorized access.


##Tools Used

Kali Linux
UFW (Uncomplicated Firewall)
Telnet (for testing blocked port)
Terminal (bash)

##Steps Performed
Step 1 — Check Firewall Status
Step 2 — Enable Firewall
Step 3 — Add Rule to Block Port 23 (Telnet)
Step 4 — Test the Rule (Try Connecting to Port 23)
Step 5 — Allow SSH Port 22
Step 6 — Remove the Block Rule
Step 7 — List All Rules



##What I Learned
How firewalls work
I learned that a firewall filters traffic based on rules.
Rules decide whether a connection should be:
Allowed (ACCEPT)
Blocked (DENY)


Difference between open and blocked ports
When port 23 was blocked, any attempt to connect to it failed.
When port 22 was allowed, SSH traffic was permitted.
How UFW simplifies firewall management
Instead of using complex iptables commands, UFW makes it easy:
deny <port>
allow <port>
status numbered
delete <rule>

Testing rules with real commands
Using telnet helped verify that the rule was actually working.

Importance of firewall in security
Firewalls prevent:
Unauthorized connections
Network attacks
Access to vulnerable services
This improves the overall security posture of a system.


##Summary of the Task

This task helped me understand how firewall rules control and filter network traffic.
I successfully:
Checked firewall status
Enabled UFW
Blocked Telnet port 23
Tested blocked traffic
Allowed SSH port 22
Removed rules to restore the system
Verified rule changes
Firewalls act as the first line of defense by controlling which ports and services are accessible.



