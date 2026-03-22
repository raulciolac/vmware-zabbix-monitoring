# VMware Zabbix Monitoring

This project demonstrates a monitoring solution for VMware infrastructure using Zabbix.

## Overview

The system monitors virtual machines hosted on VMware ESXi/vSphere and collects key metrics such as:
- CPU usage
- Memory usage
- Disk usage
- Network activity

## Architecture

- VMware ESXi/vSphere hosts virtual machines
- Zabbix Server collects monitoring data
- Zabbix Templates are used for VMware discovery and metrics
- Optional scripts interact with VMware API

## Features

- VMware host monitoring
- VM auto-discovery
- Resource usage tracking
- Alerting based on thresholds
- Modular project structure

## Project Structure

- configs/ → configuration notes
- templates/ → Zabbix templates
- scripts/ → helper scripts
- docs/ → setup documentation
- diagrams/ → architecture representation

## Purpose

This project is built for learning and demonstrating:
- Infrastructure monitoring
- Zabbix configuration
- VMware integration
- Real-world DevOps/IT monitoring concepts
