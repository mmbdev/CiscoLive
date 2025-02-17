# S16 - Solving Global WAN Challenges with Multi-Region Fabric [BRKENT-2609]

## Theoretical-Input

  - PPTX: BBRKENT-2609.pdf

## Notes

 1. Typical WAN Design Blueprint

 - Distributed SD-WAN Controllers
 - Using UX 2.0 - (NEW Tool) - Network Hierarchy Manager
  SD-WAN-Manager: Configuration > Network Hierarchy -> Enable MRF - "MultiRegionFabric"

  Workflows: Create WAN regions + and assign controllers

  Create Configuration Groups: config-group
   - Features-VPN
   - Sub Features routing
  
  Configuration can’t be easier 
   - Clear-Config-State Onepager (S71)
  
  Configure Service-VPN

  SD-WAN-Manager (vManage)
  SD-WAN-Controller (vSmart)

  Smart-Path-Filtering (MPLS-Traffic-Optimizations)
   - Route-Aggregation
  
  Monitoring -> TopoView -> Region-X

  - Migrate Access Regions (S94)

  - Affinity Group - dynamic Allocating of WAN-Streams for Lines A,B?
    - Priority for next Hop
    - Optimize Latency in WAN
    - Accellorate WAN-Szenarios

  Toolbox:
   - Afinity Group
   - Affinity Group Preference
   - Tunnel Group
  
  Fully automated via vManage (pfr3)

## Links

 - v8000; https://www.cisco.com/c/en/us/products/collateral/routers/catalyst-8000v-edge-software/catalyst-8000v-edge-software-ds.html

 - Cisco MFR; https://www.cisco.com/c/en/us/td/docs/routers/sdwan/configuration/mrf/mrf-guide/h-sd-wan-basics.html

 - PFR3.0; https://www.cisco.com/c/en/us/products/ios-nx-os-software/performance-routing-pfr/index.html
 - Branch-Routers; https://www.cisco.com/c/en/us/products/routers/product-listing.html#CloudConnectors
