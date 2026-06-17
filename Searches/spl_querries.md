# Failed Login Count
```spl
index=main EventCode=4625
| stats count as "Failed Logins"
```

# Successful Login Count
```spl
index=main EventCode=4624
| stats count as "Successful Logins"
```

# Failed Logins Over Time
```spl
index=main EventCode=4625
| timechart count
```

# Successful Logins Over Time
```spl
index=main EventCode=4624
| timechart count
```

# Failed Logins by User
```spl
index=main EventCode=4625
| stats count by Account_Name
```

# Recent Authentication Events
```spl
index=main (EventCode=4624 OR EventCode=4625)
| table _time Account_Name ComputerName EventCode
| sort - _time
```
