# Setup Guide

## Step 1: Install Zabbix Server

Install Zabbix using:
- Docker OR
- Official installation package

## Step 2: Access Zabbix UI

Open browser:
http://localhost/zabbix

Login with default credentials.

## Step 3: Configure VMware

- Add VMware ESXi / vSphere host
- Provide:
  - IP address
  - Username
  - Password

## Step 4: Import Template

- Go to:
  Configuration → Templates → Import
- Import vmware_template.xml

## Step 5: Link Template to Host

- Attach VMware template to your host
- Enable monitoring

## Step 6: Verify Data

- Check:
  Monitoring → Latest data
  Monitoring → Graphs

## Notes

- Ensure network connectivity between Zabbix and VMware host
- Credentials must have read permissions
