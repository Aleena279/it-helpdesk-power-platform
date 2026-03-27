# IT Help Desk Ticketing System (Power Platform)

End-to-end IT Help Desk system using Power Apps, Power Automate, SharePoint & Power BI with SLA tracking, workflow automation, and real-time analytics.


## 📌 Overview
This project is an end-to-end IT Help Desk solution built using Microsoft Power Platform to manage support tickets, automate workflows, and provide real-time analytics.

It simulates an enterprise IT support system with role-based access, SLA tracking, and automated escalation.

## 🏗️ Architecture
- Data Layer: SharePoint Lists (Tickets, SLA Rules, IT Team)
- App Layer: Power Apps Canvas App (3 screens)
- Automation: Power Automate (4 flows)
- Analytics: Power BI Dashboard

## 🚀 Features
- Submit and track IT support tickets
- Role-based access (Employee vs IT Agent)
- Auto-assignment of tickets based on category
- Email notifications for ticket updates
- SLA breach detection and escalation
- Weekly automated reporting
- Real-time Power BI dashboard

## 📱 Power Apps
- 3-screen Canvas App:
  - Submit Ticket Screen
  - My Tickets Screen
  - IT Agent Dashboard
- Role detection using SharePoint (IT Team list)
- Form-based ticket submission
- Status tracking with color indicators

## ⚙️ Power Automate Flows
1. Auto-Assign Ticket  
2. Status Change Notification  
3. SLA Breach Escalation  
4. Weekly Summary Report  

## 📊 Power BI Dashboard
- KPI Cards:
  - Total Tickets
  - Open Tickets
  - Avg Resolution Time
  - SLA Breach %
- Charts:
  - Tickets by Category
  - Tickets by Status
  - Trend over time
- Interactive slicers for filtering

## 🗂️ Data Model
SharePoint Lists:
- Tickets
- SLA Rules
- IT Team

## 🔄 Workflow
1. User submits ticket via Power Apps  
2. Power Automate assigns ticket to IT agent  
3. Agent updates status via app  
4. Notifications sent to user  
5. SLA monitored automatically  
6. Power BI dashboard updates in real-time  

## 📸 Screenshots

### Power Apps New Ticket Screen
<img width="1364" height="577" alt="PowerappsNewTicketScreen" src="https://github.com/user-attachments/assets/af1be51c-d89e-4160-88a3-4794d38efb88" />

### Power Apps My Ticket Screen

<img width="1366" height="572" alt="PowerappsMyTicketScreen" src="https://github.com/user-attachments/assets/93a19a0d-dcab-4d22-a0ba-1cedc00317c0" />

### Power Apps Agent Screen

<img width="1362" height="575" alt="PowerappsAgentScreen" src="https://github.com/user-attachments/assets/3b3ae67a-11fe-482d-814a-8d2f70d04b3b" />


## 🛠️ Tech Stack
- Power Apps (Canvas App)
- Power Automate
- SharePoint Online
- Power BI Desktop

## 📌 Project Highlights
- End-to-end business solution using low-code platform
- Automated workflows reducing manual effort
- SLA tracking with escalation logic
- Data-driven insights using Power BI

## 👩‍💻 Author
Aleena Thomas  
GitHub: https://github.com/Aleena279
