# vsphere-hardening-guide
vSphere Hardening Guide Compliance Scripts 
Based on VMware's Hardening Guide, version 5.5
All VMware Hardening Guides are homed at http://www.vmware.com/security/hardening-guides.html

These scripts are used in SANS SEC579: https://www.sans.org/course/virtualization-private-cloud-security

For usage:
- Open VMware PowerCLI
- Run the script with the target ESXi or vCenter host as the single argument
- Targeting a vCenter host will cover all attached ESXi hosts and VMs

Requirements:
- PowerShell version 4 or better is recommended ($PSVersionTable.PSVersion)
- PowerCLI version 5.5 release 1 or newer (Get-PowerCLIVersion)
- NMAP is required for some audit tests - install the latest version of nmap from https://nmap.org/download.html

The vCenter audit script is optimized for Windows installs, but will still run fine against the Appliance version of VC

Enjoy!
