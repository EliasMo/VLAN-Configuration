# Inter-VLAN Configuration 

## Overview 

### Purpose
  Using Inter-VLAN routing in CML to enable communication between VLANs, simulating a SOHO network with automated IP assignment and traffic control 

### Two methods
  - Router on a Stick (Cisco router and Layer 2 switch)
  - Layer 3 switch routing
  - DHCP will be included for dynamic IP assignment, ACLs for security

### Objectives
  - Configure VLANs and routing
  - Automate IPs with DHCP
  - Secure the traffic with ACLs
  - Show connectivity and restricitions

## Network Topology 
  1. Router on a Stick:
       - Devices: IOSv Router, IOSv L2 switch , 2 PCs

      ![image](https://github.com/user-attachments/assets/63e94fd1-2b4e-4ea5-9f85-179d02f35c9f)


         
  2. L3 Switch:
       - Devices: IOSv L3 switch, 2 PCs
    
      ![image](https://github.com/user-attachments/assets/e0f03261-ac71-4814-9035-b5eb27a24adf)


## Configuration 
  ### Router on a Stick Configuration:

  ![image](https://github.com/user-attachments/assets/b4232e07-f32b-4126-b22d-8c77fe085d87)

  -  Layer 2 Switch Configuration

![image](https://github.com/user-attachments/assets/cf361c19-3db9-4b53-a8bd-d296e39f16a1)

  - IOSv Router Configuration

    - Setting up DHCP,VLANs and Router-on-Stick

![image](https://github.com/user-attachments/assets/cb46c001-2ff3-4d52-a5c0-ae40e0289273)

![image](https://github.com/user-attachments/assets/3fc06894-17f4-409b-ad2e-cdd7698f3bcb)

  - Testing PCs

![image](https://github.com/user-attachments/assets/1d7db37a-e8b5-4afc-97a8-c1858c814617)

![image](https://github.com/user-attachments/assets/32f35e3a-bf56-4962-a222-4de8950c4759)


### Layer 3 Switch SVI Configuration





