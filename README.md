# Home Monitoring Lab

This repository contains the setup form monitoring devices and services in my home lab. 


## Current Status
**Monitoring Targets**:
  - Raspberry Pi 5
  - 3x Raspberry Pi 4 (Kubernetes nodes - planned)
  - Raspberry Pi 3
  - MikroTik Routers and Switch (SNMP)

**Tools Used**:
  - Prometheus
  - Grafana
  - SNMP Exporter
  - Node Exporter

## Planned Work:
- Install Node Exporter on all Raspberry Pi devices
- Install SNMP Exporter for Mikrotik router monitoring
- Configure Grafana dashboards
- Connect to Kubernetes etrics for container monitoring
- Create alerting rules and notification channel (Telegram)

## Dashboards

Once available, Grafana dashboard screenshots will be stored in `screenshots/`.

## Notes
This monitoring setup will be integrated with [home-devops-lab](https://github.com/tmaciocha/home-devops-lab)
