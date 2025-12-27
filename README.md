# 🏅 Paris Olympics 2024: Oracle APEX Management System

> **Note:** This is a **demonstration project** developed for academic purposes. While the data is modeled after the real Paris 2024 Olympics, this application serves primarily as a showcase of **Oracle APEX** implementation and advanced database management.
> 
> 

This repository documents a high-fidelity database application built on the **Oracle APEX Cloud** platform. The project focuses on creating a professional-grade user interface coupled with a complex relational back-end to manage large-scale sporting event data.

###  Core Oracle APEX Implementation

This project highlights advanced features of the Oracle APEX environment:

* 
**Custom Authentication & Security**: Implemented a `custom_auth` system with three distinct access levels—**Admin**, **Manager**, and **Reader**—to manage data entry and system settings.


* 
**Advanced UI Customization**: Beyond standard themes, the application uses **Custom CSS** for the login and home pages, and **HTML** for specialized navigation buttons and venue maps to achieve an "official website" look.


* 
**Complex Data Entry Forms**: Features **18 Reports with Forms** for standard data entry and **5 Master-Detail forms** (e.g., Team Member lists and Venue Information) for handling parent-child data relationships.


* 
**Dynamic Visualizations**: A centralized **Dashboard** integrating four distinct charts for real-time medal tracking by country.


* 
**Interactive Calendars**: Utilized the **Legacy Calendar** feature to visualize competition schedules and event timing.



###  Database & Backend Features

* 
**Relational Integrity**: Built on a detailed E-R model tracking athletes, events, rounds, results, and sponsors.


* 
**Triggers & Automation**: Employs multiple SQL triggers to automate primary key generation and maintain data consistency.


* 
**Aggregate Analytics**: Includes specialized reports based on multi-table joins and aggregate queries to generate live medal tables and discipline summaries.



### 📂 Accessing the Demo

The application was hosted in the following environment:

* 
**Workspace**: `DELULU_GIRLS` 


* 
**Application Link**: [Paris Olympics 2024 Demo](https://apex.oracle.com/pls/apex/r/delulu_girls/parisolympic2024) 



---

**Developed By**: Atkiya Maisha & Mohua Akter 

**Course**: Database Systems (CSE302) 

**Institution**: East West University
