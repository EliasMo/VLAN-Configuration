# VLAN-Configuration
## Project1 - Basic-VLAN-Segmentation 

Configuring VLANs on switches to segment a network, check connectivity and automate VLAN checks.  VLANs are used in departments to secure and manage the traffic. 

### Objective
Show VLAN isolation by creating separate broadcast domains.


### Topology
- **Devices**:
    - IOSL2 Switch
    - Alpine Desktop 1: VLAN 10, IP "192.168.1.10"
    - Alpine Desktop 2: VLAN 20, IP "192.168.1.20"
 
Topology Diagram:

![image](https://github.com/user-attachments/assets/1921d4a4-e5de-4fa1-aa89-d8c18b847646)



### Steps: 
  - Configure VLAN 10 and 20 on the switch
  - Assign Host1 to VLAN 10 and Host2 to VLAN 20 and connect them to the Switch
  - Use ping tests to show that Host 1 and 2 cannot communicate, illustrating VLAN segementation 

## Basic VLAN Segmentation 


### Steps:
1. **Configure VLAN 10 on the switch**

    ![image](https://github.com/user-attachments/assets/f813f959-3541-4e91-b544-ef26be791286)

2. **Assign the Hosts VLANs**
   - Host 1 assigned to VLAN10 on E0/0
   - Host 2 assigned to VLAN20 on E0/0

![image](https://github.com/user-attachments/assets/36eb426d-3e49-42f2-a0e8-d351ab92f6f9)

![image](https://github.com/user-attachments/assets/fc18b931-c6bc-404b-84d4-a7767d8678f3)

![image](https://github.com/user-attachments/assets/ba356b0d-3cb2-4210-b917-952665dd6107)

3. **Configure Alpine Desktops**
  - Log in root on Alpine Desktop 1
  - Put the IP Address `192.168.1.10/24` (VLAN10)
  - Put the IP Address `192.168.1.20/24` (VLAN20) for Desktop 2
  - See `Configs/alphine1-config.txt`.

![image](https://github.com/user-attachments/assets/fc3e69c2-c874-476d-b9e7-40d1a156f7bd)

![image](https://github.com/user-attachments/assets/302eec63-805c-4ac0-a219-07c4b08d1828)


![image](https://github.com/user-attachments/assets/14682d34-f8ba-4147-9ea0-48db29b62228)

![image](https://github.com/user-attachments/assets/1f57f10c-141a-4dc0-b150-258da01a8bb2)

- Apply the network changes and verify IP

![image](https://github.com/user-attachments/assets/4c5407ec-12e6-4161-9d41-48f401c6146e)

4. **Testing VLAN**

    - From Desktop 1

      ![image](https://github.com/user-attachments/assets/9c2c040d-da31-4826-b26f-2e86c0eb8ec9)

    - From Desktop 2

      ![image](https://github.com/user-attachments/assets/14e1661c-0208-4ede-8f85-5dc6ebc65057)









