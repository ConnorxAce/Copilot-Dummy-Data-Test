# Firewall Telemetry Dataset

## Overview
This is a simulated firewall environment used for testing a Copilot agent.  
There are **30 firewall devices** in this environment, named firewall1 through firewall30.  

Each firewall has the following telemetry metrics:

- CPU utilization (%)
- Memory utilization (%)
- Availability (%)
- Uptime (hours)

All telemetry data is included below in a **markdown table**, so the Copilot agent can read it directly.

---

## Firewall Telemetry Table

| Firewall  | CPU % | Memory % | Availability % | Uptime Hours |
|-----------|-------|----------|----------------|--------------|
| firewall1 | 23    | 61       | 99.98          | 1240         |
| firewall2 | 55    | 47       | 99.92          | 860          |
| firewall3 | 18    | 34       | 99.99          | 2120         |
| firewall4 | 67    | 71       | 99.80          | 420          |
| firewall5 | 42    | 50       | 99.95          | 980          |
| firewall6 | 31    | 63       | 99.91          | 1340         |
| firewall7 | 76    | 80       | 99.70          | 210          |
| firewall8 | 28    | 39       | 99.97          | 1680         |
| firewall9 | 49    | 52       | 99.90          | 770          |
| firewall10| 36    | 44       | 99.96          | 1550         |
| firewall11| 58    | 60       | 99.88          | 610          |
| firewall12| 22    | 35       | 99.99          | 2300         |
| firewall13| 64    | 70       | 99.85          | 540          |
| firewall14| 33    | 48       | 99.93          | 900          |
| firewall15| 40    | 51       | 99.95          | 1320         |
| firewall16| 27    | 37       | 99.97          | 1750         |
| firewall17| 72    | 76       | 99.78          | 350          |
| firewall18| 38    | 42       | 99.96          | 1480         |
| firewall19| 46    | 55       | 99.94          | 1190         |
| firewall20| 59    | 62       | 99.89          | 640          |
| firewall21| 24    | 36       | 99.98          | 2050         |
| firewall22| 61    | 68       | 99.87          | 510          |
| firewall23| 44    | 49       | 99.95          | 1210         |
| firewall24| 29    | 41       | 99.97          | 1620         |
| firewall25| 53    | 57       | 99.92          | 880          |
| firewall26| 35    | 46       | 99.96          | 1420         |
| firewall27| 68    | 73       | 99.83          | 470          |
| firewall28| 21    | 33       | 99.99          | 2400         |
| firewall29| 47    | 53       | 99.93          | 1100         |
| firewall30| 62    | 66       | 99.88          | 690          |

---

## Example Questions

The Copilot agent can now answer questions such as:

- How many firewalls do I have? → **30 firewalls**
- List all firewall devices → firewall1 … firewall30
- Which firewall has the highest CPU usage? → **firewall7**
- What is the uptime of firewall12? → **2300 hours**
- Which firewalls have availability below 99.9%?

---

## Notes for the Agent

- Use **only the data in this markdown file**.  
- Do not rely on any JSON files or external references.  
- All answers about firewall counts, CPU, memory, availability, or uptime must come from this table.
