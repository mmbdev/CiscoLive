# S21 - The Network of the Future is Here - Let’s Automate your IPv6 deployment with Python! [BRKOPS-2223]

## Theoretical-Input

  - PPTX: BRKOPS-2223.pdf

## Notes

 - IPv6 Recap; 
  - Link-Local fe80::/10
  - Unique-Local fc00::/7
  - Global 2000::/3

 - Automating Engine
  - NETMIKO; https://github.com/ktbyers/netmiko

   - Multi-vendor SSH Python library
   - Leverage CLI expertise
   - Simplify SSH connection to devices

   S40,41 - Example Script Snippet

 RESTCONF: https://<device>/restconf/data/Cisco-IOS-XE-native:native/interface


 YANG-Suite: https://developer.cisco.com/yangsuite/

 Netkimo vs. RESTCONF (S65)

  - Meraki Dashboard (API-Example)
  - Catalyst Center (API-Example)

  SSoT-Suggestions:

   - YAML file
   - NetBox
   - Nautobot; https://networktocode.com/nautobot/

  RFC8305 in a nutshell; (S87)

  Retrieve IPv6 client info from Catalyst Center (S105)

## Links

 - Github-Python-Link; https://github.com/juuliasantala/BRKOPS-2223
 - Juulia-Repos; https://github.com/juuliasantala