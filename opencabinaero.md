# Open Cabin Aero
[July 10th, 2024]: #
[Draft]: #
[Created: C. Hall]: #
[Contributors:   ]: #

## Specification for Open Commumincation in Aerospace Cabin Systems

## Contents 
1. General Overview
2. Scope   
3. Systems
   1. Cabin Management Systems (CMS)
      <!--- 
      1. Control
      2. Status and Reporting --->
   3. In-flight Entertainment (IFE)
      <!---
      1. Audio
      2. Video
      3. Control
      4. Status and Reporting --->
   5. Lighting
   6. Environmental Control (ECS)
   7. Cabin Networks
      <!---
      1. DHCP Server
      2. Security
      3. LAN
      4. WLAN
      5. VLAN
      6. Status and Reporting --->
10. List of Terms
11. References  
   
### 1. General Overview
### 2. Scope
This specification sets the minimum standards for communication, reporting and intergration of aerospace cabin systems. 
### 3. Systems
#### 1. Cabin Management Systems
   1. Control Methods
   **Methodology**
      CMS controls and third party interfaces should be simple to configure, command and replicate. Command and control should refrain from propritary methods and should be maintained publically (Open source).
      Benefits of this methodology include the following:
         + Faster third party integration.
         + Common training across the aviation community.
         + Faster and logical troubleshooting. 


      1. Discrete Logic 
         The use of discrete logic shall be the minimum means of system interaction.
      2. Network API 
         The system should have the capability to be commanded by a REST or WEB API.
         
   1. Status and Reporting
      1. Discrete Logic
         The use of discrete logic shall be the preferred means of system status and reporting for the following.
         + System/LRU Powered On.
         + System/LRU Failed.
       2. Network API
          The system should have the capability to be queiried by a REST or WEB API. 
          + System/LRU ON.
          + System/LRU Failed.
          + System/LRU Failed Code or reason (ASCII).
#### 2. In-flight Entertainment (IFE)
   1. Audio
   2. Video
   3. Control
   4. Status and Reporting
         
#### 3. Lighting
#### 4. Environmental Control (ECS)
#### 5. Cabin Networks
1. DHCP Server
   + There shall be one (1) dedicated DHCP server for the cabin
   + TBD
3. Security
   + TBD
5. LAN
   + TBD
7. WLAN
   + Wireless Access points shall have an external discrete interface to control the RF radios
   + 
9. VLAN
   + VLANs 1-9 shall be reserved for router and WAN related interfaces.
     
10. Status and Reporting
  1. Discrete Logic
     The use of discrete logic shall be the preferred means of system status and reporting for the following.
     + System/LRU Powered On.
     + System/LRU Failed.
     + WLAN Status
  2. Network API
     The system should have the capability to be queiried by a REST or WEB API.
     + System/LRU ON.
     + System/LRU Failed.
     + System/LRU Failed Code or reason (ASCII).
  3. MQTT
     + TBD
### 10. List of Terms
API: Application Programming Interface  
CMS: Cabin Management System  
ECS: Environmental Control System  
IFE: In-flight Entertainment  
LRU: Line Replaceable Unit  

### 11. References
[MQTT](https://mqtt.org/)
