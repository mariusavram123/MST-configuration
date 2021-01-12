This project has been build using the GNS3 network emulator.

The goal of this lab is to configure multiple spanning-tree on a 3-switches redundant network as follows:

A:

- Configure VLANs 100, 200, 300 and 400.
- Assign vlans 100 and 300 to the MST instance 1.
- Assign vlan 200 to the MST instance 2.
- VLAN 1 and VLAN 400 will remain assigned to default MST instance(0).

B:

- Assign SW1 as the root bridge for instance 1 and the secondary root bridge for instance 2.
- Assign SW3 as the root brodge for instance 2 and the secondary root bridge for instance 1.

C:

- Set the spanning-tree mode to MST.
- Set the e2/0 ports on SW1 and SW2 and e2/0 and e2/1 on SW3 as edge ports.

D: 

- Set e2/0 port on SW1 as access port in VLAN 100
- Set e2/0 port on SW2 as access port in VLAN 300
- Set e2/0 port on SW3 as access port in VLAN 200
- Set e2/1 port on SW3 as access port in VLAN 400
