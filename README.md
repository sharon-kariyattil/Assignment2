# Employee Dashboard

An employee task management web application that supports role-based login (admin and employee) and provides features like task creation, updating, marking as completed/failed, and viewing task statistics.

## User Login Credentials

Below are the default login credentials to access the application:

### Admin Login

- **Email:** admin@example.com
- **Password:** 123

### Employee Logins

1. **Employee 1:**

   - **Email:** e@e.com
   - **Password:** 123

2. **Employee 2:**

   - **Email:** employee2@example.com
   - **Password:** 123

3. **Employee 3:**
   - **Email:** employee3@example.com
   - **Password:** 123

and so on....

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sharon-kariyattil/employee-management-system
   ```
2. Navigate to the project directory:
   ```bash
   cd employee-management-system
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

```
📦
├─ .gitignore
├─ README.md
├─ eslint.config.js
├─ index.html
├─ logo.svg
├─ package-lock.json
├─ package.json
├─ postcss.config.js
├─ public
│  └─ vite.svg
├─ src
│  ├─ App.jsx
│  ├─ assets
│  │  └─ react.svg
│  ├─ components
│  │  ├─ Auth
│  │  │  └─ Login.jsx
│  │  ├─ Dashboard
│  │  │  ├─ AdminDashboard.jsx
│  │  │  └─ EmployeeDashboard.jsx
│  │  ├─ TaskList
│  │  │  ├─ AcceptTask.jsx
│  │  │  ├─ CompleteTask.jsx
│  │  │  ├─ FailedTask.jsx
│  │  │  ├─ NewTask.jsx
│  │  │  ├─ TaskList.jsx
│  │  │  └─ taskUtils.js
│  │  └─ other
│  │     ├─ AllTask.jsx
│  │     ├─ CreateTask.jsx
│  │     ├─ Header.jsx
│  │     └─ TaskListNumbers.jsx
│  ├─ context
│  │  └─ AuthProvider.jsx
│  ├─ index.css
│  ├─ main.jsx
│  └─ utils
│     ├─ authUtils.js
│     ├─ localStorage.jsx
│     └─ toastConfig.js
├─ tailwind.config.js
└─ vite.config.js
```

## Screenshots

![Login Page](/public/login.png) </br>
![Employee Dashboard](/public/employee-dashboard.png) </br>
![employees](/public/employees.png) </br>
![task overview](/public/task-overview.png)
