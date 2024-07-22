# Open Cabin Aero
[July 10th, 2024]: #
[Draft]: #
[Created: D. Hall]: #

## Specification for Open Commumincation in Aerospace Cabin Systems

### Contents 
1. General Overview
2. Scope
   This specification sets the minimum standards for communication, reporting and intergration of aerospace cabin systems. 
3. Systems
   1. Cabin Management Systems (CMS)
      1. Control
      2. Status and Reporting
   2. In-flight Entertainment (IFE)
      1. Audio
      2. Video
      3. Control
      4. Status and Reporting
   3. Lighting
   4. Environmental Control (ECS)
   5. Cabin Networks
      1. DHCP Server
      2. Security
      3. WLAN
4. List of Terms
5. References  
   
### 1. General Overview
### 2. Scope
### 3. Systems
#### 1. Cabin Management Systems (CMS)
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
          The system should have the capability to be queiried by a REST or WEB API. The API should follow the system methodology in **Section 3.1.1**.
          + System/LRU ON.
          + System/LRU Failed.
          + System/LRU Failed Code or reason (ASCII).
##### 2. In-flight Entertainment (IFE)
   1. Audio
   2. Video
   3. Control
   4. Status and Reporting
         
##### 3. Lighting
##### 4. Environmental Control (ECS)
##### 5. Cabin Networks
          
### 4. List of Terms
API: Application Programming Interface  
CMS: Cabin Management System  
ECS: Environmental Control System  
IFE: In-flight Entertainment  
LRU: Line Replaceable Unit  

### 5. References
