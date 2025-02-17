# S22 - Packet Journey inside Catalyst 9000 Switches [BRKARC-3090]

## Theoretical-Input

  - PPTX: Comming Soon

Init-Reads-2-Recap:

- ASIC-Def; https://www.techopedia.com/definition/2357/application-specific-integrated-circuit-asic

## Notes

his session dives into how Catalyst 9000 switches handle packet forwarding to streamline traffic path verification and troubleshooting. We’ll explore various packet-handling scenarios, including:

    Catalyst 9000 data plane architecture: An overview of UADP and SiliconOne models
    Transit packet flow: How packets pass through the switch
    In-band packet flow to the CPU: Understanding in-band management traffic
    Unicast packet forwarding: Tracing the unicast forwarding path
    Multicast replication: Investigating how multicast packets are replicated
    Diagnosing packet drops and forwarding issues: Practical insights for tackling packet handling problems

--
 - One Family from Access to Core – Common Hardware & Software (S19)
 - UDAP -> Cisco Silicon One ASICs; (Own CL Topic ASICS)
  - https://www.ciscolive.com/c/dam/r/ciscolive/global-event/docs/2022/pdf/BRKARC-2091.pdf 
 - Control Plane Policy CoPP Overview (S71,S72)
 
 Debugging, Capturing of Packet-Flows:
 - Forwarding Tracking Tools (S91)
  - show platform Forward; show platform hardware fed active forward … 
  - Packet State Vector; debug platform hardware fed active capture …
  - Show Platfrom Forward: show platform hardware fed switch [1|2|..] forward interface GigabitEthernet 1/0/22

 - Take away:
  - Importance of Packet Journey Analysis
  - Data Plane vs. Control Plane
  - Catalyst 9000 as a campus networking platform
  - Built-In Tools for Packet Path Analysis

## Links

- Unified Access Data Plane ( UADP ); https://community.cisco.com/t5/networking-blogs/uadp-the-powerhouse-of-catalyst-9000-family/ba-p/3764605
- ASICs; https://www.ciscolive.com/c/dam/r/ciscolive/global-event/docs/2022/pdf/BRKARC-2091.pdf