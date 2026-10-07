# LGU-Governance-System

A desktop-based Local Government Unit (LGU) management dashboard built with Java Swing and MySQL. This system facilitates role-based workflows for municipal operations, including business permit processing, budget expense tracking, and transparent auditing. 

Role-Based Portals

<img width="381" height="242" alt="image" src="https://github.com/user-attachments/assets/b1517b99-de6c-4517-8f04-cc6481c0b386" />

Public Citizen Portal: Allows citizens to submit business permit applications (New/Renewal) and view approved municipal budget transparency ledgers.

Assessor Dashboard: Enables municipal assessors to review, evaluate, and approve/deny pending business permit applications.

Staff Dashboard: Allows municipal staff to encode localized department expenses, attach project details, and route budgets for approval.

Treasurer Dashboard: Provides financial oversight to sign, approve, or deny pending municipal budget requests.

VPC Shield Audit Ledger

<img width="830" height="587" alt="image" src="https://github.com/user-attachments/assets/7370744f-d025-4072-b9c2-0d05b966f481" />

Automated Tracking: Utilizes automated MySQL Database Triggers (AFTER INSERT, AFTER UPDATE) to silently log all system actions.

Role Attribution: Captures the exact user_role (CITIZEN, ASSESSOR, STAFF, TREASURER) and associates it with specific actions and timestamps.

CSV Export: One-click data extraction allowing administrators to export the full audit ledger to a .csv file for external reporting.


Frontend: Java Swing (GUI)

Backend: Java (Core)

Database: MySQL (JDBC connector)

Architecture: Object-Oriented Programming (OOP), MVC-inspired DAO pattern
