# Firewall Telemetry Dataset

## Overview
This file contains simulated firewall telemetry data for testing Copilot agents.  
It represents a dynamic environment where devices can be added or removed, and telemetry metrics are updated periodically.

Currently, there are **30 firewall devices** named firewall1 through firewall30.  
Each firewall has the following metrics:

- CPU utilization (%)  
- Memory utilization (%)  
- Availability (%)  
- Uptime (hours)

---

## Firewall Telemetry Table

| Firewall  | CPU % | Memory % | Availability % | Uptime Hours |
|-----------|-------|----------|----------------|--------------|
| firewall1 | 22    | 58       | 99.95          | 1340         |
| firewall2 | 35    | 49       | 99.90          | 870          |
| firewall3 | 19    | 36       | 99.99          | 2120         |
| firewall4 | 65    | 72       | 99.83          | 410          |
| firewall5 | 42    | 51       | 99.94          | 980          |
| firewall6 | 30    | 63       | 99.91          | 1320         |
| firewall7 | 75    | 79       | 99.70          | 220          |
| firewall8 | 28    | 38       | 99.97          | 1690         |
| firewall9 | 50    | 52       | 99.90          | 760          |
| firewall10| 37    | 45       | 99.96          | 1500         |
| firewall11| 56    | 60       | 99.88          | 620          |
| firewall12| 24    | 34       | 99.99          | 2300         |
| firewall13| 63    | 69       | 99.86          | 540          |
| firewall14| 33    | 48       | 99.93          | 910          |
| firewall15| 41    | 52       | 99.95          | 1310         |
| firewall16| 27    | 37       | 99.97          | 1740         |
| firewall17| 71    | 75       | 99.78          | 360          |
| firewall18| 39    | 43       | 99.96          | 1490         |
| firewall19| 45    | 55       | 99.94          | 1200         |
| firewall20| 60    | 61       | 99.89          | 650          |
| firewall21| 25    | 36       | 99.98          | 2050         |
| firewall22| 62    | 67       | 99.87          | 510          |
| firewall23| 44    | 50       | 99.95          | 1220         |
| firewall24| 29    | 41       | 99.97          | 1630         |
| firewall25| 54    | 57       | 99.92          | 890          |
| firewall26| 36    | 46       | 99.96          | 1400         |
| firewall27| 67    | 73       | 99.83          | 480          |
| firewall28| 21    | 33       | 99.99          | 2410         |
| firewall29| 47    | 53       | 99.93          | 1110         |
| firewall30| 61    | 65       | 99.88          | 700          |

---

## Notes for Dynamic Updating

- This file can be updated hourly by a script.  
- New firewalls can be added (e.g., firewall31) or removed.  
- Metrics (CPU, Memory, Availability, Uptime) should be refreshed hourly.  
- Keep the markdown table format intact for Copilot to read it.

---

## Example Questions for the Agent

- How many firewalls are currently listed?  
- List all firewall device names.  
- Which firewall has the highest CPU usage?  
- What is the uptime of firewall12?  
- Which firewalls have availability below 99.9%?  

---

*This dataset is fully self-contained. Do not reference any JSON files or external sources.*
