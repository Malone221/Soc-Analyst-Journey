Week 0 – SOC Lab Setup Checklist

Virtual Machines
Installed VMware
Create Windows 10 VM (for user/attacker simulation)
Create Linux VM (Kali)
Create Windows Server VM (for AD simulation)

Networking
Configure NAT/Bridged network for internet access
Ensure VMs can ping each other
Document IP addresses of all VMs

Security Tools
Install Sysmon on Windows endpoint
Install log forwarder (Winlogbeat/Agent) to send logs to SIEM
Deploy SIEM (Wazuh / Splunk Free / ELK)
Confirm logs are visible in SIEM

Documentation & Proof
Write notes.md in this folder
Upload screenshots (/week0-setup/screenshots/)
Update README.md in root with progress


Completion Status
All required VMs are running
Repo updated with notes & screenshots
