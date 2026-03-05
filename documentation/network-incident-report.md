# Network Connectivity Incident Report

## Incident Summary

A user reported that the server was unable to reach external websites and internet connectivity appeared to be unavailable.

## Investigation Steps

Step 1: Verified network connectivity using the ping command.

Command used:

ping google.com

Observation:
The server successfully reached Google's servers and returned multiple ICMP responses.

Step 2: Verified network interface configuration.

Command used:

ip a

Observation:
The network interface was active and assigned a valid IP address.

Step 3: Verified system resource usage.

Command used:

top

Observation:
System CPU and memory usage were within normal operating levels.

Step 4: Verified disk storage availability.

Command used:

df -h

Observation:
The server had sufficient available disk space and no storage-related issues.

## Resolution

Network connectivity was confirmed to be operational.  
The issue was determined to be unrelated to server networking.

## Skills Demonstrated

• Incident response troubleshooting  
• Network diagnostics  
• Linux system administration  
• Command-line troubleshooting
