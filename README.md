<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Installation Configuration


## Environments and Technologies Used
- Microsoft Azure (Virtual Machines)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)
- MySQL Database
- osTicket (v1.15+)

## Operating Systems Used
- Windows 10 (21H2)

## Objectives
- Build an organized help desk structure  
- Define agent permissions and access boundaries  
- Configure departments and teams for accurate ticket routing  
- Establish SLA plans to ensure timely response  
- Set up user authentication rules and help topics  
- Simulate real help desk operations end-to-end  

# Core Configuration Overview


### Scenario 1 – Online Banking Outage (High Priority)

### What Happened  
A user submitted a ticket saying the entire mobile banking system was down.

### Key Actions  
- created the ticket
 <img width="759" height="948" alt="image" src="https://github.com/user-attachments/assets/49de5175-5723-4264-ac9b-e0c8e94a1576" />
 
- Reviewed the ticket details to confirm the problem  
- Set the SLA to a high-priority plan (Sev-A)  
- Assigned the ticket to the Online Banking team and document problems
 <img width="767" height="924" alt="image" src="https://github.com/user-attachments/assets/d3d4fa90-37ed-4c5e-8f99-47678b8d9548" />

- Documented troubleshooting steps  
- Identified a failed update, rolled it back, and restored service
- Assign the ticket to Jane Doe from the Online banking team
  <img width="759" height="229" alt="image" src="https://github.com/user-attachments/assets/709169f3-cf10-464b-9ade-f9be24775a94" />

- changed the priority to emergency because I forgot in the first step
- Closed the ticket once the system was working again
  <img width="757" height="865" alt="image" src="https://github.com/user-attachments/assets/f11a35ab-3de8-4c82-b217-054f2e567761" />


### Why these actions matter  
Major outages impact many users, so classifying them correctly ensures they are handled immediately.  
Documenting the steps helps the team understand what happened and prevents repeated mistakes.

### Skills Learned  
- Prioritizing high-impact issues  
- Using SLAs correctly  
- Routing issues to the right team  
- Troubleshooting system-wide outages  
- Writing clear technical updates  


### Scenario 2 – Adobe Software Not Working (Low Impact)

### What Happened  
Several accounting users could not open Adobe Reader.

### Key Actions 
- create ticket
<img width="760" height="943" alt="image" src="https://github.com/user-attachments/assets/e0eb4d7b-7d83-4111-b7fd-b362c0915e01" />

- Set the SLA to a low-priority option (Sev-C)  
- Assigned the ticket to the appropriate agent  
- Performed simple troubleshooting and confirmed a restart fixed the issue  
- Documented the solution and closed the ticket
  <img width="1512" height="956" alt="image" src="https://github.com/user-attachments/assets/6c18b9fe-2dbc-4ae5-b7c2-18896fa42506" />



### Why these actions matter  
Most help desk issues are minor, and correctly classifying them prevents them from delaying more important work.  
Simple fixes still need clear documentation so the next agent knows what was done.

### Skills Learned  
- Handling day-to-day support requests  
- Using SLAs to separate minor issues from critical ones  
- Basic software troubleshooting  
- Writing accurate resolution notes  


### Scenario 3 – CFO’s Laptop Not Working (High Impact User Issue)

### What Happened  
A ticket was submitted because the CFO’s laptop would not turn on.

### Key Actions 
- created ticket
  <img width="1506" height="958" alt="image" src="https://github.com/user-attachments/assets/338d7ad1-7051-4740-a2ac-b7dbe7e25269" />

 - Set a more urgent SLA (Sev-B) because it involved an executive  
- Investigated the issue  
- Found the problem was a broken charger  
- Replaced the charger and confirmed the laptop worked  
- Documented the fix and resolved the ticket
  <img width="1469" height="950" alt="image" src="https://github.com/user-attachments/assets/26b31f96-70ff-42a9-966f-08991559d275" />


### Why these actions Matter  
Even simple problems become high impact when they involve critical users.  
Learning to evaluate impact, not just the technical problem, is an important help desk skill.

### Skills Learned  
- Understanding business impact  
- Prioritizing based on user role  
- Hardware troubleshooting  
- Professional communication and documentation  


### Summary

This project shows real help desk responsibilities: taking in user issues, classifying them correctly, troubleshooting problems, documenting everything, and closing tickets. It demonstrates technical ability, communication skills, and the decision-making needed in an IT support role.

