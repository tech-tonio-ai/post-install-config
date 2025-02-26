<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This guide walks through the complete setup and configuration of osTicket. We cover installation, role and department management, user and agent setup, SLA configuration, and ticketing system customization. By following these steps, you'll have a fully functional osTicket system ready for managing support tickets efficiently.  


## osTicket Configuration  

### 1. Acknowledge Agent Panel vs Admin Panel
<p align="center">
  <img src="https://i.imgur.com/Csb96vB.png" alt="Image 1" width="45%"/>
  <img src="https://i.imgur.com/1f4HXRM.png" alt="Image 2" width="45%"/>
</p>

### 2. Configure Roles (Grouping Permissions)  
- **Path:** `Admin Panel -> Agents -> Roles`  
- Example Role: **Supreme Admin**
<p align="center">  
  <img src="https://i.imgur.com/sEOyAZG.png" alt="Image 2" width="45%"/>
    
</p>  

### 3. Configure Departments (Ticket Visibility)  
- **Path:** `Admin Panel -> Agents -> Departments`  
- Example Department: **SysAdmins**  
<p align="center">  
  <img src="https://i.imgur.com/P9pn9fq.png" alt="Image 2" width="45%"/>
    
</p> 

### 4. Configure Teams  
- **Path:** `Admin Panel -> Agents -> Teams`  
- Teams allow agents from different departments to collaborate.  
- Example Team: **Online Banking**
<p align="center">  
  <img src="https://i.imgur.com/sdpf4zl.png" alt="Image 2" width="45%"/>
    
</p> 

### 5. Allow Anyone to Create Tickets  
- **Path:** `Admin Panel -> Settings -> User Settings`  
- **Uncheck:** "Unregistered users can create tickets"  
- **Enable:** "Registration Required" (Users must register and log in to create tickets)
<p align="center">  
  <img src="https://i.imgur.com/AbMN7xT.png" alt="Image 2" width="45%"/>
    
</p> 

### 6. Configure Agents (Workers)  
- **Path:** `Admin Panel -> Agents -> Add New`  
- Example Agents:  
  - **Jane** (Dept: SysAdmins)  
  - **Jorge** (Dept: Support)  
<p align="center">  
  <img src="https://i.imgur.com/6KcQKjS.png" alt="Image 2" width="45%"/>
    
</p>

### 7. Configure Users (Customers)  
- **Path:** `Agent Panel -> Users -> Add New`  
- Example Users:  
  - **Karen**  
  - **Ken**  
<p align="center">  
  <img src="https://i.imgur.com/pwUwYw9.png" alt="Image 2" width="45%"/>
    
</p>

### 8. Configure SLA (Service Level Agreement)  
- **Path:** `Admin Panel -> Manage -> SLA`  
- Example SLAs:  
  - **Sev-A** (Grace Period: **1 hour**, Schedule: **24/7**)  
  - **Sev-B** (Grace Period: **4 hours**, Schedule: **24/7**)  
  - **Sev-C** (Grace Period: **8 hours**, Schedule: **Business Hours**)
<p align="center">  
  <img src="https://i.imgur.com/Wzu7t5j.png" alt="Image 2" width="45%"/>
    
</p>

### 9. Configure Help Topics (Ticket Categories)  
- **Path:** `Admin Panel -> Manage -> Help Topics`  
- Example Help Topics:  
  - **Business Critical Outage**  
  - **Personal Computer Issues**  
  - **Equipment Request**  
  - **Password Reset**  
  - **Other**
  
<p align="center">  
  <img src="https://i.imgur.com/d1CeO4L.png" alt="Image 2" width="45%"/>
    
</p>

