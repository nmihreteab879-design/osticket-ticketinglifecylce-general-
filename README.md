<p align="center">  
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>  
</p>  

# osTicket - Ticket Lifecycle Lab  

This project demonstrates the complete lifecycle of tickets in osTicket, an open-source help desk system. The lab focuses on simulating real-world IT support operations, including ticket creation, assignment, updates, escalation, and resolution.  

The scenarios highlight essential IT support skills such as incident prioritization, troubleshooting, escalation management, workflow efficiency, and clear communication with end-users.  

## Environments and Technologies Used  
- Microsoft Azure (Virtual Machines / Compute)  
- Remote Desktop Protocol (RDP)  
- Internet Information Services (IIS)  
- MySQL Database  
- osTicket (v1.15+)  

## Operating Systems  
- Windows 10 (21H2)  

## Objectives  
The main goals of this lab were to:  
- Demonstrate the full ticket lifecycle from creation to resolution  
- Handle incidents of varying priority, including high-impact and executive-level issues  
- Apply SLA plans and adjust priorities based on ticket urgency  
- Document troubleshooting, escalation, and resolution steps  
- Collaborate effectively between agents and teams  
- Simulate end-user ticket submissions and agent interactions  

## Ticket Scenarios  

### Scenario 1: Mobile Online Banking Outage  
A widespread outage prevented customers from accessing online banking services. As an end user, a ticket was submitted describing the issue. As an agent, the ticket was categorized, assigned to the Online Banking team, and given a high-priority SLA. The problem was investigated, the root cause identified, and communication was maintained with the end user until service was restored.

Skills Demonstrated:  
- Assigning tickets to the correct team and agent  
- Applying SLA plans and adjusting priorities for urgent issues  
- Troubleshooting and documenting the root cause  
- Updating ticket status and communicating resolution  

 <img width="759" height="948" alt="image" src="https://github.com/user-attachments/assets/49de5175-5723-4264-ac9b-e0c8e94a1576" />

Created a new ticket so the agents can deal with the issue. Creating the initial ticket represents how users report issues in a real environment. This step initiates the workflow and allows IT teams to track, assign, and prioritize incidents systematically instead of handling them informally.

  <img width="767" height="924" alt="image" src="https://github.com/user-attachments/assets/d3d4fa90-37ed-4c5e-8f99-47678b8d9548" />
 
 I Assigned the ticket to the Online Banking team and applied the Sev-A SLA to reflect the system-wide outage and left a description of the problem. 
 
 <img width="766" height="952" alt="image" src="https://github.com/user-attachments/assets/d465f0ca-ce79-467b-98da-74f654e62ace" />
 
 I logged in as an agent named jane and assigned the ticket to myself
 
 <img width="759" height="229" alt="image" src="https://github.com/user-attachments/assets/709169f3-cf10-464b-9ade-f9be24775a94" />
 
 I documented all the things I did to solve the problem and what I did to resolve it 
 
 <img width="757" height="865" alt="image" src="https://github.com/user-attachments/assets/f11a35ab-3de8-4c82-b217-054f2e567761" />
 
  I changed the priority to emergency in this step because I missed this step earlier and I resolved the ticket because the problem was solved


### Scenario 2: Accounting Software Issue  
Users in the accounting department were unable to access the Adobe suite required for their daily tasks. The issue was logged, prioritized, and assigned to the appropriate agent. After identifying the cause as a licensing configuration error, the software access was restored and affected users were informed of the resolution.  

 <img width="760" height="943" alt="image" src="https://github.com/user-attachments/assets/e0eb4d7b-7d83-4111-b7fd-b362c0915e01" />
 
 I created a new ticket
 
-<img width="1512" height="956" alt="image" src="https://github.com/user-attachments/assets/6c18b9fe-2dbc-4ae5-b7c2-18896fa42506" />

I assigned the ticket to john doe I made the priority normal, and I made the sla sev-c. 


### Scenario 3: CFO Laptop Problem  
The CFO reported that their laptop would not power on, representing a high-priority executive issue. The ticket was escalated immediately and given an emergency SLA. After diagnosing a hardware failure, a replacement device was deployed and verified as fully functional. The incident and resolution steps were documented for tracking purposes.  

<img width="1506" height="958" alt="image" src="https://github.com/user-attachments/assets/338d7ad1-7051-4740-a2ac-b7dbe7e25269" />

I created a new ticket

<img width="1469" height="950" alt="image" src="https://github.com/user-attachments/assets/26b31f96-70ff-42a9-966f-08991559d275" />

I changed the sla to sev-b I assigned it to a specific agent named jhon doe then I logged in as jhon doe and solved the issue. I also documented this 


## Key Takeaways  
- Managing the entire ticket lifecycle improves efficiency and accountability in IT support  
- SLA plans and prioritization ensure the most critical issues receive timely attention  
- Clear documentation and communication lead to faster resolutions and better user satisfaction  
- Hands-on work with Azure, IIS, MySQL, and osTicket reinforces real-world technical support experience  
- Practical simulation of IT workflows builds readiness for help desk and system administration roles  

## Skills Demonstrated  
- Ticket lifecycle management (creation, escalation, and closure)  
- Application of SLA plans and incident prioritization  
- Troubleshooting and root cause analysis  
- Documentation and technical communication  
- End-user support and customer service  
- Workflow management within ticketing systems  
- Collaboration between IT departments and teams  
- Familiarity with Azure-hosted environments and IIS configuration  
