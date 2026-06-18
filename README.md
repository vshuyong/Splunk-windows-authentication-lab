# Splunk-windows-authentication-lab
## Overview

This project demonstrates the use of Splunk Enterprise to monitor and analyze Windows authentication activity.

## Architecture
![Splunk Windows Authentication Monitoring Architecture](screenshots/Splunk-windows-authentication-monitoring-architecture.png)

## Objectives

- Detect failed login attempts
- Detect brute-force attacks
- Monitor successful logins
- Monitor account lockouts
- Create dashboards and alerts
- Document findings

## Tools

- Splunk Enterprise
- Windows Event Logs
- SPL (Search Processing Language)

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


## Skills Demonstrated

- Splunk Enterprise Administration
- Windows Event Log Analysis
- SPL Query Development
- Dashboard Creation
- Authentication Monitoring
- Brute-force Detection
- Security Event Investigation


## Future Improvements

- Create alerts for repeated failed login attempts.
- Add account lockout monitoring using Event ID 4740.
- Add more Windows Security Event IDs.
- Build additional authentication dashboards.
