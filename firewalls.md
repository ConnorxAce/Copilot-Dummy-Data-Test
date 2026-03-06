# Firewall Telemetry Dataset

## Overview

This document describes a simulated firewall monitoring environment used for testing a Copilot agent.

The environment contains **30 firewall devices**. Each firewall has monitoring telemetry similar to what a network monitoring platform such as SolarWinds would collect.

The firewall telemetry data includes the following metrics:

* Firewall name
* CPU utilization percentage
* Memory utilization percentage
* Availability percentage
* Device uptime in hours

The raw telemetry data for all firewalls is stored in a JSON dataset located in:

data/firewalls.json

This dataset represents the monitoring information collected for all firewalls in the environment.

---

## Firewall Inventory

The environment currently contains **30 firewall devices**.

Firewall device names:

firewall1
firewall2
firewall3
firewall4
firewall5
firewall6
firewall7
firewall8
firewall9
firewall10
firewall11
firewall12
firewall13
firewall14
firewall15
firewall16
firewall17
firewall18
firewall19
firewall20
firewall21
firewall22
firewall23
firewall24
firewall25
firewall26
firewall27
firewall28
firewall29
firewall30

---

## Monitoring Metrics Collected

Each firewall in the dataset has the following telemetry attributes:

CPU Utilization
Represents the current processor usage of the firewall as a percentage.

Memory Utilization
Represents the current memory usage of the firewall as a percentage.

Availability
Represents the operational availability of the firewall expressed as a percentage.

Uptime
Represents how long the firewall has been running without reboot, measured in hours.

---

## Example Firewall Telemetry Record

A typical firewall monitoring record looks like this:

Firewall Name: firewall1
CPU Utilization: 23 percent
Memory Utilization: 61 percent
Availability: 99.98 percent
Uptime: 1240 hours

---

## Dataset Usage

This dataset is intended for testing a Copilot agent that answers operational questions about firewall infrastructure.

Example questions the agent should be able to answer include:

* How many firewalls are in the environment?
* List all firewall devices.
* Which firewall has the highest CPU utilization?
* What is the memory usage of firewall7?
* Which firewalls have availability below 99.9 percent?
* What is the uptime of firewall12?

When answering these questions, the agent should reference the firewall telemetry dataset.

---

## Summary

Total firewalls in environment: 30

Firewall devices included in the dataset:
firewall1 through firewall30.

Each firewall has telemetry data including CPU usage, memory usage, uptime, and availability.

The telemetry dataset is stored in the JSON file located at:

data/firewalls.json
