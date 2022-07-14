## Introduction to Root Switch 

In spanning tree topology, Switches elect a root switch based on the BID(Bridge ID). And The root switch is the switch with the lowest numeric value for BID. We all know that BID is divided into two part, first one is priority value, essentially the switch that have lowest priority become root switch in Spanning Tree Topology.Second part is Universal MAC was used to create the BID for each switch. Sometime Between switches the priority selection has tie, then switches start electing the root switch with Lowest Mac address portion of the BID. 


## Misson
- In this lab, You need to configure the Priority value of the root switch to become root switch in spanning-tree-topology.


## Hint
- STP/RSTP works by default on Cisco Switch, so all the settings needed by a switch have a default value. However switch have default BID, based on a default priorty value and adding a Universal Mac address that comes with the switch hardware, Also switch have default Administrative cost/root cost based on the current operating speed of the switch interfaces.
- I think You ignore the lab-4, If yes then go there and Take something from lab4 and use it 


Thank You
