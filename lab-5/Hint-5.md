## Interface are not Working Status
Cisco switches use two different sets of status code. On set of two status code that are also used in routers interface status code. and another set of one status code(Word).

let's talk about Single status Code is basically a word that tells the interface are working or not, (Connected, notconnect). Now what about two status code refer the line status and protocol status
The Line status tell about layer 1 working, and Protocol status tell the layer 2 working. 

## Misson 
 - In this lab, You need to troubleshoot the interface, and find the problem 


## Hint 
- The following table list the code combination and define some problem that are commonly occure on interfaces.

<table>
<tr>
<td> 

## Switch inteface Status Code

|    Line Status       | Protocol Status      | Interface Status | Description                                                                                                                                                                            | 
|----------------------|----------------------|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Administratively Down|  Down                | Disabled         |      Interface was not working because of the command was used on it                                                                                                                   | 
|                      |                      |                  |                                                                                                                                                                                        | 
| Down                 |   Down               | notconnect       |     Might be possible, that there is no cable, wrong cable pinouts, or there is sometime speed mismatch, or there is possiblity the neigboring deice is powered off, or error-disabled |       
|                      |                      |                  |                                                                                                                                                                                        | 
| Up                   |    Down              | notconnect       |    Not expected on lan switch physical interfaces                                                                                                                                      |   
|                      |                      |                  |                                                                                                                                                                                        |      
| Down                 |   Down(Err-Disabled) | err-disabled     |    Port security has been disabled the interface                                                                                                                                       |       
|                      |                      |                  |                                                                                                                                                                                        |
| up                   |   up                 |  Connected       |       The interface is working perfectly                                                                                                                                               |     

</td>
</tr>
</table>


Thank You
