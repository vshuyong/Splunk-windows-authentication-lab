# Splunk-windows-authentication-lab
## Overview
**Project Type:** SIEM Authentication Monitoring Lab  
**Environment:** Windows 11, Splunk Enterprise, and Splunk Universal Forwarder

This project demonstrates the use of Splunk Enterprise to monitor and analyze Windows authentication activity.

## Architecture
![Splunk Windows Authentication Monitoring Architecture](screenshots/Splunk-windows-authentication-monitoring-architecture.png)

This architecture shows how Windows Security Event Logs (Event IDs 4624 and 4625) are collected by the Splunk Universal Forwarder, indexed in Splunk Enterprise, analyzed using SPL searches, visualized through dashboards, and used for security monitoring and incident analysis.

## Objectives

- Detect failed login attempts
- Detect brute-force attacks
- Monitor successful logins
- Monitor account lockouts
- Create dashboards and visualizations
- Document findings and observations

## Technologies Used

- Splunk Enterprise
- Splunk Universal Forwarder
- Windows 11
- Windows Security Event Logs
- SPL (Search Processing Language)
- GitHub

## Project Structure

```text
screenshots/
searches/
documentation/
sample-data/
```

## Detection Use Cases

1. Failed Login Detection
2. Successful Login Monitoring
3. Brute Force Detection
4. Account Lockout Detection
5. Authentication Dashboard

## Windows Event IDs Monitored

- Event ID 4624 – Successful logon
- Event ID 4625 – Failed logon attempt

## Screenshots

### Main Dashboard
![Windows Authentication Dashboard](screenshots/windows-authentication-monitoring-dashboard.jpg)


### Main Dashboard (Part 2)
![Windows Authentication Dashboard - Part 2](screenshots/windows-authentication-monitoring-dashboard-2.jpg)


### Main Dashboard (Part 3)
![Windows Authentication Dashboard - Part 3](screenshots/windows-authentication-monitoring-dashboard-3.jpg)


### Failed Login Events Search
![Failed Login Events Search](screenshots/failed-login-events-search.jpg)


### Failed Logins by User
![Failed Logins by User](screenshots/failed-logins-by-user-search.jpg)


### Failed Logins by Workstation
![Failed Logins by Workstation](screenshots/failed-logins-by-workstation.jpg)


### Successful Login Events Search
![Successful Login Events Search](screenshots/successful-logins-events-search.jpg)


### Successful Logins by User
![Successful Logins by User](screenshots/successful-logins-by-user-search.jpg)


### Successful Logins Over Time
![Successful Logins Over Time](screenshots/successful-logins-over-time-search.jpg)


### Main Index Search
![Splunk Main Index Search](screenshots/splunk-main-index-search.jpg)

## Key Findings

- Successfully ingested Windows Security logs into Splunk Enterprise.
- Created SPL searches to identify successful and failed logins.
- Visualized authentication activity through dashboards and charts.
- Demonstrated the ability to investigate authentication events and identify suspicious login patterns.


## Skills Demonstrated

- Splunk Enterprise Administration
- Windows Event Log Analysis
- SPL Query Development
- Dashboard Development and visualization 
- Authentication Monitoring
- Brute-force Detection
- Authentication Event Investigation


## Future Improvements

- Create alerts for repeated failed login attempts.
- Implement account lockout detection using Event ID 4740.
- Add more Windows Security Event IDs.
- Build additional authentication dashboards.
- Configure Splunk alerts for suspicious authentication activity.
