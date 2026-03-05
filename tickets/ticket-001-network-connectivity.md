# Ticket #001 – Network Connectivity Issue

## User Report
User reports that the server cannot access external websites and internet connectivity appears to be unavailable.

## Priority
Medium

## Troubleshooting Steps

Step 1: Tested network connectivity.

Command used:

ping google.com

Result:
Server successfully returned ICMP responses from Google's servers.

Step 2: Checked network interface configuration.

Command used:

ip a

Result:
Network interface enp0s3 was active and assigned an IP address.

## Resolution

Connectivity to external hosts was confirmed.  
Issue was not related to the server network configuration.

## Status
Resolved
