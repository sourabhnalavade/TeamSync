# TeamSync – A Task & Team Management Web Application  

TeamSync is a web-based task and team management application built with Angular 18 and Tailwind CSS. It helps teams streamline their workflow by allowing employees and managers to manage tasks, track project progress, and monitor leave details efficiently.  

## Features  

### Authentication & User Management  
- Secure Signup & Login using JSON Server  
- Role-Based Access (Employee & Manager)  
- Employee profile with personal details  

### Task Management  
- Task Assignment: Managers can assign tasks to employees  
- Task Status Updates: Employees can mark tasks as To Do, In Progress, or Completed  
- Task Search & Filtering  
- Comments: Employees can add comments to tasks  
- Multiple Views: Kanban, List, and Calendar  

### Dashboard & Analytics  
- Employee Dashboard: View assigned tasks and personal leave details  
- Manager Dashboard: Monitor team tasks & leave requests with graphs  

### UI Components & Navigation  
- Sidebar Navigation (Dynamic based on user role)  
- Navbar with Logged-in User Info  
- Logout Button for session termination  

## Tech Stack  
- Frontend: Angular 18 (Standalone Components), Tailwind CSS  
- Backend: JSON Server (Mock API for tasks & users)  
- State Management: LocalStorage for session persistence  

## Installation & Setup  

### Clone the Repository  
```sh
git clone https://github.com/your-username/TeamSync.git
cd TeamSync
