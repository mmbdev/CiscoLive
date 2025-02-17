# S3 - Automate Network Operation Tasks with NetDevOps and Source of Truth [BRKOPS-2357]

## Theoretical-Input

  - PPTX: BRKOPS-2357.pdf

#Netbox #SSoT #pyTAS #Gitlab

## Notes

Provider/Business-UseCase:
 - Rätische Bahn

- DevNetAcad
- Automated Staging Setup - FASS (Ansible, Netbox, DHCP, TFTP)
   - deploy a new Site

 - Workflow:Description
  > Netbox Script, Webhooks
  > Gitlab CI/CD Pipeline
  > CatalystCenter: Site+Floor created

Deep-R1:
 - Component-View; Deploy / Test
 - Diff between IPAM // DCIM // SoT
 - Benefit no Spreadsheets anymore

Deep-R2:
 - https://docs.netboxlabs.com/netbox-integrations/pyats/
  - Ansible-Dev-Template : TAG for Catalyst Center

Deep-R3:
 - Ansible Explenation
  - Playbook: Play, Task, Module
  - Inventroy

Deep-R4:
 - Test pyATS
  - CommonSetup
  - Testcase
  - CommonCleanup

CD+CD -> Orchestrator of Ansible / PyATS

## Links

https://github.com/pamosima/BRKOPS-2357

https://developer.cisco.com/
https://devnet-academy.com/ 