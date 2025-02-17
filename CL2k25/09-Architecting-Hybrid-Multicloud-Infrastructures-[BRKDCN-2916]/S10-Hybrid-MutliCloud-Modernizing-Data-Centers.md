# S10 - Modernizing Data Centers: Accelerate with Automation and Expertise [WOSCX-1336]

## Theoretical-Input

  - PPTX: BRKDCN-2916.pdf

## Notes

 - Taxonomy
 - Cloud Terminology Matrix

 - Multi Cloud Connectivity and Routing
  - Colo East / West (S13)

 - Architecture
   - Secure-Networking, AppData
   - AI-Apps standalone topic
   - Topology of DC, Colo
  
  - Capabilities: Site/User-to-Cloud
  
  - Connecting Devices to Cloud
   - Catalyst SD-WAN-Manager as a Broker (S25)
  
  - Mutli-Cloud-Workflow
   - Tenant-based
   - AWS/Azure: Region2Region
   - AWS/Azure: Site-to-Site
   - AWS/Azure: Site-to-Cloud

  - CatalystManager
   - Onboarding Brownfield, Legacy via BGP session vHub

  - Site2MultiCloud; 
   - SD-WAN-Tunnels
   - Colo: Megaport, Equinix
    - DirectConnect
    - ExpressRoute
    - Interconnect

   - Fully Encrypted L2, L3 posibillity of MACSec, IPSEC
    - ECMP is comming soon
  
 - Cloud to Cloud: Private Connect (S41)
 - SRC -> DST - SGT to defince Routing+SEC-Policy

Use-Cases:
  1. IT-User, IoT-User - (RA-VPN}
  - Cisco SSE/SASE - Cisco Secure Client, NewRequirements of FATClient

 - SecurityCloudControl (S52), Really Need or nice2have 4 Sec?
 - ZTNA Struct of Cisco (End to End Segmented Traffic + Enforcement), (S53)

  virtual-Appliances:
  - Cat8v
  - NGFWv

  - VirtualPrivateCloud (VPC)-Tags
  - FireallManagementCenter (FMC) vApp
  - Cisco Secure Workload (CSW) vApp - to control (ISE + FMC)
    -> Segmentation Policy Enforcement, virutalMachines, Containers, ...
  - IdentityServiceEngine (ISE) vApp or OnPrem

  2. MultiCloud-Defense
  Cloud networking, automation, and cloud-native network security controls

    virtual-Appliances:
    - MultiCloud Defense Controller
  
  - Ingress / Egress Gateway (S70)
  - Security Models
    - Centralized, Distributed, Combined

 - AWS Centrelized East-West-Inter-VPC
 
 3. App2App
 - Transparently secures Application-to-Applications (SDWAN + NGFWv + MCD)

 X. Summary of DC, Colo, Hyper (S79)
 
  Common Policy (82)
  - Content Exchange Hub; ISE - SGT-based
   - per Tenant - Layer3-Out:InterVRF

 -> SDWAN: SD-WAN-Manager, vSmart, vFMC
  - MicroSegmentation / Service Chaining
  - VXLAN GPO
Inside each use case is the ability to apply policy for Micro-Segmentation
and/or Service-Chaining.

 Visability:ThousendEyes (AWS-InterRegio E-W)

 - Splunk - Digital Resilience - last Point 
  - All-Data-Into-the-Platform 
  -> Outcome of Visability, Insights, ProactiveResponse

## Links
 FAQ-v-Session:
 - Hosting-Engine: https://www.techrepublic.com/article/megaport-virtual-edge-vs-equinix-network-edge/
 - About CiscoSecRAClient: https://www.stratusinfosystems.com/anyconnect-comparison-guide/

 Fundamentals:
 - https://datatracker.ietf.org/doc/html/draft-smith-vxlan-group-policy-03

 IaaC:
 - https://registry.terraform.io/namespaces/CiscoDevNet
 - https://galaxy.ansible.com/cisco