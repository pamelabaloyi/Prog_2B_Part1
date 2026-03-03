Contract Monthly Claim System (CMCS)

Overview

The Contract Monthly Claim System (CMCS) is a role-based web application prototype designed to streamline monthly claim submissions and approvals for Independent Contractor (IC) lecturers.
The system models a real-world enterprise approval workflow with structured role separation and relational database design.

Current version: Frontend prototype (UI only). Backend and database integration planned.

User Roles

Lecturer – Submit monthly claims, upload documents, track status

Programme Coordinator – Review and process claims

Academic Manager – Final approval and oversight

Core Entities

*Lecturer

*Claim

*SupportingDocument

Relationships:

*One Lecturer → Many Claims

*One Claim → Many Supporting Documents

Tech Stack

C#

.NET Core (WPF / ASP.NET MVC

SQL Server (Planned)

Git & GitHub

Author

Pamela Baloyi

(Software Development)
