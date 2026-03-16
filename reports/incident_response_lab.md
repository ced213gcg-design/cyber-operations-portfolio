# Incident Response Lab

## Scenario
Security monitoring detected a suspicious process running on a workstation.

## Objective
Investigate the potential compromise and outline containment and response procedures.

## Investigation Steps

### Step 1 – Identify Suspicious Process
Check running processes for anomalies.

Example command:
ps aux

Look for:
- unknown processes
- unusual CPU usage
- unexpected network connections

### Step 2 – Verify Network Activity
Check active connections.

Example command:
netstat -tulnp

Look for:
- unknown external connections
- suspicious listening ports

### Step 3 – Containment
If malicious activity is suspected:

- isolate affected system
- disable compromised accounts
- block suspicious IP addresses

### Step 4 – Evidence Collection
Preserve system evidence for analysis:

- system logs
- running process list
- network connection records

### Step 5 – Recovery
Restore system integrity:

- remove malicious software
- patch vulnerabilities
- reset compromised credentials

## Conclusion
The incident response process ensures rapid containment of threats while preserving evidence for further investigation.
