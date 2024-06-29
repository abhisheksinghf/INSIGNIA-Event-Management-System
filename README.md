# Insignia Event Management System

Welcome to the Insignia 24 Event Management System! This project is designed to streamline and manage the various activities and events for the college fest, Insignia, conducted by Shri Dharmasthala College of Engineering and Technology, Dharwad.
**The system was executed flawlessly during Insignia 2024 without any errors.**

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Modules](#modules)
  - [Admin Module](#admin-module)
  - [Event Coordinator Module](#event-coordinator-module)
  - [Desk Manager Module](#desk-manager-module)
  - [Monitor Module](#monitor-module)
- [Contact](#contact)

## Introduction

Event Management System is a web-based application developed to manage the planning, organization, and execution of events for the college fest, Insignia, conducted by Shri Dharmasthala College of Engineering and Technology, Dharwad. This system aims to streamline event registration, payment management, and overall event coordination, eliminating the need for Google Forms. 

## Technologies Used

- **Frontend:** ![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
- **Framework:** ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
- **Backend:** ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
- **Email Service:** ![AWS SES](https://img.shields.io/badge/AWS%20SES-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

## Features

✨ **Dashboard:** Get a comprehensive overview of total participants, paid participants, accommodation details, event counts, and financial statistics.
  
👥 **User Management:** Easily create and manage users with different roles such as Admin, Event Coordinator, Desk Manager, and Monitor.
  
📅 **Event Management:** Seamlessly add and manage event information, including images and basic details.
  
📝 **Participant Management:** View and export participant details in various formats for easy tracking and record-keeping.
  
🔍 **Custom Filtering:** Filter participants based on events and payment status to quickly access the required information.
  
📧 **Email Notifications:** Automatically send confirmation emails to participants after registration.
  
💳 **Payment Management & Bill Generation:** Efficiently add, view, and manage payment details, and generate bills with ease.
  
📂 **Data Export:** Export participant and event data into PDF and Excel formats for convenient record-keeping.
  
🔐 **Secure Authentication:** Ensure data security with robust authentication mechanisms for all users.
  
📱 **Responsive Design:** Access the system on-the-go with a responsive, mobile-friendly interface.
  
🔧 **Separate Panels:** Different logins and panels for Event Coordinators to manage their specific tasks efficiently.

## Modules

### Admin Module

The Admin Module provides comprehensive control and oversight over the entire event management system. Key features include:

- **Dashboard:** Displays total participants, paid participants, accommodation details, total events, and financial details including amounts collected from various events (technical, cultural, centralized) and total collected via cash and online payments.
  ![Admin Dashboard](screenshots/admin/admin_dash.png)

- **Manager Panel:** Allows the creation of users for different roles such as admin, coordinator, and desk manager.
  ![Manager Panel](screenshots/admin/manager_panel.png)

- **Events:** Add event information along with images and basic details.
  ![Events](screenshots/admin/event_half.png)
  ![Events](screenshots/admin/event_full.png)
  ![Events](screenshots/admin/event_add.png)

- **Participants:** View participant details and export them in Excel or PDF format.
  ![Participants](screenshots/admin/particpant_full.png)

- **Custom Filters:** Filter participants based on events and payment status (paid and unpaid).
  ![Custom Filters](screenshots/admin/custom.png)

### Event Coordinator Module

The Event Coordinator Module is designed for coordinators to manage participants and event details efficiently. Key features include:

- **Dashboard:** Overview of total participants, paid participants, total groups, and paid groups.
  ![Coordinator Dashboard](screenshots/coordinator/coordinator_dashboard.png)
  ![Coordinator Dashboard](screenshots/coordinator/coordinator_dashboard_full.png)

- **Paid Participants:** View and export details of paid participants in various formats.
  ![Paid Participants](screenshots/coordinator/co-part.png)

- **Unpaid Participants:** View details of unpaid participants.
  ![Unpaid Participants](screenshots/coordinator/unpaid-par.png)

- **How to Use:** Guidelines and instructions for using the system.
  ![How to Use](screenshots/coordinator/guide.png)

### Desk Manager Module

The Desk Manager Module focuses on managing on-site participant payments and registration. Key features include:

- **Desk Main Panel:** Add payment details with search functionality and a simple UI that includes bill number, amount, payment mode, and confirmation button.
  ![Desk Main Panel](screenshots/desk/main-desk.png)

- **Payment Details:** View payment details with payment IDs and export them.
  ![Payment Details](screenshots/desk/pay-det.png)

- **Bill Generator:** Generate bills by entering a special ID.
  ![Bill Generator](screenshots/desk/bill-gen.png)

### Monitor Module

The Monitor Module is designed to provide an overview and detailed filtering of event participants. Key features include:

- **Participant Filtering:** Filter event participant details based on events and payment details.
  ![Participant Filtering](screenshots/monitor/moni.png)



