# S8 - One Fabric, Many Clouds: SD-WAN Across Multi-Region Azure and Oracle Clouds-BRKCLD-2243

In today's rapidly evolving hybrid cloud environments, organizations are increasingly adopting a multicloud strategy to optimize performance, cost, and availability. This session provides a strategic roadmap for the design, deployment, and migration of a multicloud environment using Cisco SD-WAN with a focus on integrating Azure Virtual WAN (vWAN) and Oracle Cloud Infrastructure (OCI), leveraging both manual and automated approaches to accelerate transformation and minimize operational risk.

This session will cover key parts of SD-WAN design, including:

    Integrate SD-WAN data centers and branches with Azure vWAN and Oracle Cloud Infrastructure across multiple regions to enable optimized multicloud routing
    Combining manual steps with automated workflows for seamless and efficient SD-WAN integration
    A hybrid migration method that keeps the business running while switching to SD-WAN
    Moving workloads smoothly between cloud and on-premises with minimal disruption
    Smart traffic routing that uses both MPLS and the internet to balance performance and cost

---
Session Type: Breakout
Technical Level: Intermediate
Technology: SD-WAN, Cloud Native, Enterprise Architecture
Percentage of New Content: 75% New
---


Design: Dynamic_MultiVPN + iperf3.0 -> 8000v Routers on V-Hubs (full-mashed)

HW:
 - 9000er https://www.cisco.com/c/en/us/support/docs/switches/catalyst-9200-series-switches/220197-use-iperf-on-catalyst-9000-switches-to-p.html
 - 8000er ... search for papers

Migration-Strategy:
 0. Install Router-base / WAN-Manager "Perhaps without Manager" - Code-hardbase Routing-Config

 1. - Traffic-Forwarding to new virtual Hub ; dont interrupt of Connectivity like Multi-VPN
 -> Underlay non SDWAN (only Tunnel Connections)
 -> Overlay with SD-WAN (Traffic Optimization)
  . express Route Gateway /// Route-Filters
 
 2. Run BGP with Multiple Hub

 3. Azure vWAN Manual Workflow
  - Manual vs. Automated Workflow
   - 8000v from Marketplace
   - map to virtual Hub
   - discover infra and map to Service-VPN
   - vnet has deployed in SD-WAN-Manager

to innitiate disconnect - vnet > broken!!!

 4. Key-TakeAways

  - Multi-Cloud Simplified
  - Migration-Strategy
  - Automation Workflow
  - Operation and Future Architecture

Training_Links:
 - https://www.cisconetsolutions.com/iperf-network-testing-and-troubleshooting-tool/
 - https://documentation.meraki.com/Platform_Management/Dashboard_Administration/Troubleshooting_and_Support/Troubleshooting/Troubleshooting_Client_Speed_using_iPerf