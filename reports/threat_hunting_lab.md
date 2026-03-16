# Threat Hunting Lab

## Scenario
Security monitoring identified unusual authentication behavior and repeated failed login attempts across multiple systems.

## Objective
Proactively hunt for indicators of compromise by reviewing logs, identifying suspicious behavior, and forming a security hypothesis.

## Hunting Process

### Step 1 – Define the Hunt Question
Are repeated failed logins and unusual access times indicators of brute-force or unauthorized access attempts?

### Step 2 – Review Available Data Sources
Example sources:
- /var/log/auth.log
- /var/log/secure
- SIEM authentication dashboards
- firewall connection logs

### Step 3 – Identify Indicators
Look for:
- repeated failed login attempts
- successful logins after multiple failures
- access from unknown IP addresses
- unusual login timing
- repeated attempts across multiple accounts

### Step 4 – Form a Hypothesis
A threat actor may be attempting credential stuffing or brute-force access against exposed accounts.

### Step 5 – Validate Findings
Correlate login events with:
- source IP address
- username targeted
- timestamp patterns
- post-login activity

## Findings
Example indicators discovered:
- multiple failed logins from the same IP range
- unusual login times outside expected user activity
- repeated targeting of privileged accounts

## Security Recommendation
- Enforce multi-factor authentication
- Monitor suspicious IP ranges
- Configure account lockout controls
- Alert on repeated failed logins to privileged accounts

## Conclusion
Threat hunting improves visibility by proactively identifying suspicious behavior before a confirmed incident fully develops.
