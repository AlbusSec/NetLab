## Introduction to VLAN Trunking Protocol 

vlan trunking is a algorithm of VLAN tagging concept, In which switch encapsulate the ethernet header on vlan trunk=king header, but how switch identify where they can encapsulate the ethernet header to vlan trunking, or not. So Between a switches we need to configured that interface as trunk mean if switch wants to forward the frame on this interface, the switch will be encapsulate that ethernet frame into vlan header. In VLAN Headerthere is filed called VLAN Identifier(VLAN ID) that tells the switch that the frame is come which vlan. Todays Netowkring world, 902.1Q protocol was used in switch for Vlan Trunking


## Misson 
- As a Network Engineer, Your responsbility to check that vlans are working properly.

## Hint 
- Suppose, You wants to down an interface. but You doesn't not want to go to the switch, and remove a cable, For this Network Engineer Use Shutdown command on that interface to disabled that interface
- All interface are default set on dynamic auto, that's sometime make problem


Thank You
