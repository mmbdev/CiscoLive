# S13 - Nexus-as-Code - Kick-Start Your Automation with ACI [BRKDCN-2673]

## Theoretical-Input

  - PPTX: BRKDCN-2673.pdf

## Notes

- Nexus as a Module
- YAML-Layout / tree -L 2

- Use Visual Studio Completion
   YAML Extension (by RedHat)
   File-EXtension .nac.yaml

- Pre-Change Validation
 -> iac-validate -h

- Tools like Yamale can be used to define the schema and validate YAML files against
 - https://github.com/23andMe/Yamale

- Nexus Dashboard Insights (NDI
  - Simulating; Emulating SW+HW -> DigitalTwins : Test-Impact of a Change before to apply to productive ENV
  - Network Assurance Engine , nexus-pcv -h (S33)

  - Robot Framework tests using Jinja templating , iac-test
  
  - CI/CD Workflow (Dev, Pull, Main (S37)

Models:
 - NDO - Controller Centric Data Model
 - SD-WAN - Controller Centric Data Model

 - Evolution to … Network as Code (S44)

Refs:
• Nexus as Code; https://cisco.com/go/nexusascode
• Demo Repository; https://github.com/netascode/BRKDCN-2673-Demo
• Cisco Lifecycle Service – Services as Code; https://www.cisco.com/site/us/en/services/lifecycle-services/index.html
• SDWAN, Catalyst Center, ISE, NX-OS, IOS-XE, IOS-XR Terraform Providers; https://registry.terraform.io/search/providers?q=CiscoDevNet
• Network as Code; https://netascode.cisco.com

## Links

 - Simple-Case-Demo; https://github.com/netascode/nac-aci-simple-example

 - CI, CD-Demo: https://github.com/netascode/BRKDCN-2673-Demo
  