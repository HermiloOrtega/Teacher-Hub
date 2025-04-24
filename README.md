# 📦 TeacherHub

## 🧭 Overview
**TeacherHub** is a secure, Windows-based desktop application fully developed and architected by me as part of my university’s social service program. Originally inspired by my first internship at ICC School, this project aimed to digitize and centralize teacher record management. 

It became the foundational project of my proposed startup idea, **M&M System**, which I envisioned launching with a colleague—combining my software development with his IT support services.

The app replaced all paper-based teacher documentation with a fully interactive, data-rich, and secure desktop experience. Hosted internally at ICC School, it significantly reduced administrative workload and improved access control and data accuracy.

### Loading page
![Screenshot](./assets/2.png) <!-- Replace with your image path -->

### Home Page
![Screenshot](./assets/4.png) <!-- Replace with your image path -->

### New Teacher
![Screenshot](./assets/7.png) <!-- Replace with your image path -->

## 💡 Idea & Concept
TeacherHub was born from my direct experience with administrative inefficiencies during my internship. The goal was to:
- Build a high-fidelity, scalable record management system.
- Eliminate the risk of data redundancy and outdated documents.
- Provide secure access control for sensitive information.
- Support future modules like attendance tracking and teacher talent search.

This became my first **end-to-end enterprise application**, designed, developed, and deployed entirely by me, working closely with school administrators and directors to iterate and improve over several months.

## ✨ Features & Functionality
- ✅ **Login with Encrypted Credentials** and animated **progress bar** to visualize resource loading.
- 📁 **Teacher Record Management** with fields for:
  - Name, First Name, Gender (Dropdown), Blood Type, Religion
  - Height, Weight, Birthplace, Address
  - SSN and sensitive personal data
  - Relationship status, partner info, rent status and amount, relocation availability
  - Full academic history: high school, post-secondary, graduate education
  - Detailed studies, courses (multi-entry), languages (multi-entry), hobbies (multi-entry with sub-properties)
  - Family details: full names, relationships, birth dates, dependency status, employment/education
  - Full employment history: role, duration, responsibilities, and employer data
  - Profile photo integration

- 🧭 **Main Menu Options**:
  - New Teacher
  - Search & Filter
  - Job Opportunities / Career Database
  - Attendance Tracker (Planned)

- 📄 **Crystal Reports Integration** for exportable summaries
- 📥 CSV Import utility (planned and partially implemented)
- 🔍 Search/Filter capability with sorting and criteria refinement

## ⚙️ Tech Stack
- **Language**: C#
- **Platform**: Windows Forms (.NET Framework)
- **Database**: SQL Server
- **Dev Tools**: Visual Studio, SQL Server Management Studio, Crystal Reports
- **Deployment**: Internal ICC School network (local desktop installation)

## 🏗 Architecture & Design
- Designed using .NET layered architecture
- Strong focus on **data normalization** and **referential integrity**
- Connection to SQL Server via ADO.NET and stored procedures
- Login system with hashed passwords and session tracking
- Input validation, dropdowns, and dynamic form rendering for better UX
- Optimized database schema with indexing for high-performance queries

## 🚀 Installation & Setup
- **Requirements**: Windows OS, .NET Framework, SQL Server
- **Setup**: Installed on authorized school machines via MSI installer
- **Access**: Local only with role-based credentials

> **Note**: Deployment and backup policies coordinated with school IT staff.

## 🧑‍💻 My Role & Contributions
- 🛠 Full project ownership from idea to delivery
- 🧱 Designed SQL Server schema with indexed tables and constraints
- 🔐 Built secure authentication using hashed credentials and access logging
- 📊 Integrated Crystal Reports for print/export functionality
- 🧪 Managed UAT cycles with school staff and adjusted based on feedback
- 🤝 Served as project lead, analyst, designer, and developer in direct coordination with school leadership

## 🧗 Challenges & Learnings
- First production-grade app built with WinForms and SQL Server
- Learned how to implement secure authentication, UI forms, and form validation
- Built a system to handle a **complex schema** with over 100 data input points per teacher
- Gained real-world experience in gathering user requirements and iterating under feedback
- Started learning **performance tuning** for SQL queries and database design
- Implemented form-state management and lazy loading of large datasets for performance

## 📈 Future Enhancements
- Migration to a web-based app using ASP.NET MVC or Blazor
- Build-in PDF generation for documents and reports
- Role management (Admin vs HR vs Director)
- Full attendance dashboard with biometric or QR code integration
- Import wizard with duplicate detection and data validation

## 🤝 Contributing
Internal proprietary application. Maintained by ICC School. Enhancements coordinated via internal IT team.

## 🪪 License
⚠️ **License Update**  
Originally released under MIT. As of April 22, 2025, this project follows the **CC BY-NC-ND 4.0** license.  
See LICENSE file for usage limitations.

## 🔗 Additional Resources
- **Further Documentation**: Available upon request
- **Microsoft Relevance**: Demonstrates C#, SQL Server, Crystal Reports, WinForms, and system architecture skills aligned with Microsoft’s enterprise development standards