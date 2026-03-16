# Security Log Analysis Lab

## Scenario
A monitoring alert indicates unusual login activity on a system.

## Objective
Analyze authentication logs to identify potential malicious activity.

## Investigation Process

### Step 1 – Review Authentication Logs
Examine system authentication logs for failed login attempts.

Example sources:
- /var/log/auth.log
- /var/log/secure

### Step 2 – Identify Suspicious Patterns
Look for indicators such as:
- repeated failed login attempts
- logins outside normal hours
- unknown IP addresses

### Step 3 – Correlate Events
Determine if login attempts were followed by successful access.

### Step 4 – Determine Source
Identify IP addresses involved in the activity and check geolocation.

## Findings
Example indicators discovered:
- repeated failed login attempts
- login attempts from unknown IP ranges
- unusual login timing

## Security Recommendation
- Enable multi-factor authentication
- Implement account lockout policies
- Monitor suspicious IP ranges
