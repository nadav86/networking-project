----------------------------
NETWORKING: FINAL PROJECT -KERNELIOS COLLEGE
----------------------------

course name:   Networking, Kernelios
College for cyber-security
name: nadav morris
grade: 100
----------------------------
----------------------------

The project is implemented as follows:
1. VLANs
          a. Division into VLANs-
Subnetting:
                  VLAN 10: 40 PCs
VLAN 50:  100 PCs
                  VLAN 20: 12 PCs
VLAN 60:  50 PCs
                  VLAN 30:  8 PCs
VLAN 70:   2 PCs
                  VLAN 40:  4 PCs
VLAN 80:   2 PCs

                  VLAN 90:  30 PCs
VLAN 130:  85 PCs
                  VLAN 100: 30 PCs
VLAN 140:  40 PCs
                  VLAN 110: 20 PCs
VLAN 150:  12 PCs
                  VLAN 120: 15 PCs
VLAN 160:   3 PCs


             One computer is added to
represent each VLAN.

          b. Implementation on the
relevent switches (access & trunks).
          c. Implementation on the
relevent routers using the "router on a 
stick" protocol.

2. WAN + Routing
        a. Implementing networks between
routers to create a WAN.
        b. Implementing routing
protocols:
                 * OSPF Between routers R0, R1,
   R2,R3
                 * Default route (static)
Between routers R0, R1, R2, R3, R4, and
floating route


3. DHCP Protocol:
          a. Setting R0 as a DHCP Server.
          b. Creating a pool for VLAN 10
and VLAN 50, VALN 60 (remote networks).


4. NAT Protocol:

           Implementing NAT in R3 for all
VLANs towards network 192.168.5.0 .


5. VTP + PVST Protocols:

       a. VTP for all VLANs with VTP
server: SW1.
       b. PVST between SW0, SW1, SW2,
      SW3.


6. SSH Protocol:
        Enabling SSH on SW0 named "SW1".
        User : nadav
        Password: 123456


7. Port Security Protocol:

         Configuring prot security on SW1, PC2 (VLAN 90).


8. Setting passwords on a Switch:

        Setting passwords in SW1-
User EXEC mode- 1234
Priviliged EXEC mode- 12345
maybe the opposite :)


9. ACL

   Placed a standard ACL blockage preventing LAN3
   from having communication with VLAN 150 by black list.
