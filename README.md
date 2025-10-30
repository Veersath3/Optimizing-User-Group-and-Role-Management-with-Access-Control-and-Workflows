# ServiceNow Project – Optimizing User, Group, and Role Management with Access Control and Workflows  

## Project Overview  
This ServiceNow project demonstrates how to build a secure and efficient **role-based task management system**.  
It focuses on creating users, groups, and roles, implementing role-based access control (RBAC), automating workflows, and visualizing task progress with dashboards and reports.  

---

## Key Features  

### 1. User, Group, and Role Management  
- Created users (e.g., Alice – Project Manager, Bob – Team Member).  
- Formed user groups: **Project Managers** and **Team Members**.  
- Defined custom roles: `project_manager`, `team_member`, `admin`.  
- Assigned roles to users and mapped them to groups for structured access.  

### 2. Custom Scoped Application – Project Task Tracker  
- Built a scoped application named **Project Task Tracker**.  
- Designed a custom table **Project Task** with fields: Task Name, Description, Status, Assigned To, Due Date, Created By.  
- Centralized all task-related operations in one place.  

### 3. Role-Based Access Control (ACLs)  
- Implemented ACLs to restrict CRUD operations.  
- **Project Managers**: Full access (create, update, delete tasks).  
- **Team Members**: Limited access (read and update only assigned tasks).  
- Enforced conditions using **Requires Role** and condition builder.  

### 4. Application Navigation  
- Created a custom **Application Menu** named *Project Task Tracker*.  
- Added a module **All Tasks** for quick access to tasks.  
- Restricted module visibility based on roles.  

### 5. Workflow Automation (Flow Designer)  
- Automated status updates to reduce manual effort.  
- Flow logic:  
  - **Trigger**: Task record updated.  
  - **Condition**: "Assigned To" is not empty.  
  - **Action**: Status automatically updates to *In Progress*.  

### 6. Dashboards & Reports  
- Built reports for better insights:  
  - Pivot Table grouped by Task Name.  
  - Pie Chart grouped by Task Status.  
  - Pie Chart grouped by Assigned Users.  
- Combined reports into a **dashboard** for real-time monitoring.  

---

## Outcome  
✅ Improved visibility and accountability of tasks.  
✅ Secure role-based access to prevent unauthorized modifications.  
✅ Reduced manual updates through automation.  
✅ Real-time task monitoring with visual reports.  

---

## Why This Project Is Useful  
- Helps teams stay organized with clear role definitions.  
- Enhances collaboration and transparency.  
- Scales easily for larger projects.  
- Demonstrates practical usage of **ServiceNow Access Control, Flow Designer, and Reporting**.  

---

## Repository Structure  
- **Documentation/** → Detailed explanation with screenshots.    
- **README.md** → Project introduction and setup guide.  

---

## Conclusion  
This project showcases how **users, groups, roles, ACLs, workflows, and dashboards** in ServiceNow can be combined to create a real-world role-based project management solution.  
