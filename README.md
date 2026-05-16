# Campus Network Design (Cisco Packet Tracer)

A simulated multi-building campus network designed and configured in Cisco Packet Tracer. Models a real university campus topology with VLAN segmentation, inter-VLAN routing, and dynamic routing protocols, structured to reflect how enterprise and institutional networks are actually built.

---

## Network Design

The simulation covers two network deployments:

**Campus Network (`fast-campus-network.pkt`)**
- Multi-building topology with hierarchical design (core → distribution → access)
- VLAN segmentation per department (faculty, students, admin, labs)
- Inter-VLAN routing via Layer 3 switch
- RIP / static routing between buildings
- DNS, DHCP, and HTTP servers configured

---

## Files

```
Campus-Network-Designed-in-Cisco-Packet-Tracer/
├── fast-campus-network.pkt       ← campus topology (open in Packet Tracer)
├── network-diagram.png           ← screenshot of full topology
├── project_report.pdf            ← full design documentation
└── README.md
```

---

## How to Open

1. Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (free with Cisco NetAcad account)
2. Open the `.pkt` file
3. Use the simulation mode to test ping, routing, and VLAN behaviour

---

## Tools Used

- Cisco Packet Tracer
- Protocols: VLANs, RIP, OSPF, NAT, DHCP, DNS

---

## What I Learned

- How VLANs segment traffic without physical separation
- Inter-VLAN routing and why a Layer 3 switch is used at distribution layer
- How DHCP, DNS, and HTTP servers integrate into a network topology
- Relevance to industrial networks — same VLAN/routing principles apply in SCADA and IoT infrastructure
