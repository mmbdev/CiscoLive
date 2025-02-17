# S2 - BGP EVPN in Enterprise Campus with Catalyst 9000 Switching Platforms [TECENS-2680]

## Theoretical-Input

  - PPTX: TECENS-2680.pdf

## Notes

Border – Catalyst 9000 System Modes (S127)
 - DataCenter, EVPN, IP/MPLS, SD-WAN, Internet
  - Standalone only L3
  - StackWise Virtual-Mode L2, L3 Handoff
  - ESI Multihome Mode - L2, L3 Handoff

 Layer2-Handoffs (S129)
 - EVPN1, EVPN2
  - L2 VLAN Handoff (Terminate Bridge Domain)
  - VPLS Handoff (Interworking Bridge Domain)
  - EVPN Fabric (Multi-Site-L2 Extensions)
 "VLAN into VNI" 

 Layer3-Handoffs (S137)
  - IP VRF Handoff, (Terminating Routing Domain)
  - MPLS VPN Handoff, (Interworking Overlay), Overlay should be the same
  - EVPN-Fabric, (Re-origitnating Fabric Domain)

 Fabric Deplyoment Options:
  - Control Plane: LISP, BGP-EVPN)
  - HW-Controller (S142)
  - Underlay DYI: DNAC-Templates, Progammable (TERRAFORM; Ansible), CLI

User/Admin Experience CatalystCenter Process-WorkFlow (S148)
- Network-Design
- Underlay
  - L3-Access, StackWise-Virtual (VSS)
- Overlay
  - Grouping Spine, Leafs
- Assurance

LabContent:
 - LiveDemo "OnTrack"