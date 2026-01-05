# Employee Management System

## 📌 Project Overview
This is a React-based Employee Management System that allows users to manage employee data through a user-friendly dashboard.  
The application supports mock-based login authentication, employee listing, filtering, and add/edit/delete operations.

---

## 🛠 Tech Stack Used
- **Frontend:** React.js (Functional Components, Hooks)
- **Routing:** React Router DOM
- **State Management:** React `useState` & `useEffect`
- **Styling:** CSS (External stylesheet)
- **Mock Data:** JavaScript files (No backend)
- **Build Tool:** Vite
- **Browser APIs:** Window Print, File Upload (Image preview)

---

## 🧠 Assumptions
- Authentication is handled using mock credentials (no backend integration).
- Employee data is stored in local JavaScript files.
- The application is intended for single-user demo purposes.
- No persistent storage is used (data resets on refresh).

---

## 🎯 Design Decisions
- Reusable Employee Form for both Add and Edit operations.
- Client-side routing for smooth page navigation.
- Combined filtering (Search + Gender + Status) for better user experience.
- Conditional styling to visually differentiate active employees.
- UI kept simple and clean without external UI libraries.

---

## 🔄 Application Flow – Employee Management System

### 🔐 Login Flow
- The user opens the Login page.
- The user enters login credentials.
- **Mock Credentials:**
  - Username: `admin`
  - Password: `Admin@123`
- If the credentials do not match, an error message is displayed:
  > *Invalid username or password.*
- Upon successful authentication, the user is redirected to the Dashboard page.

---

### 📊 Dashboard Overview
The Dashboard provides:
- Total employee count
- List of employees with detailed information
- Search and filter options:
  - Name
  - Gender
  - Active / Inactive status
- Actions:
  - Add Employee
  - Edit Employee
  - Delete Employee
  - Print employee data

---

### ➕ Add / ✏️ Edit Employee Flow
- Clicking **Add Employee** or **Edit** redirects the user to the Employee Form page.
- The form allows the user to:
  - Enter or update employee details
  - Upload a profile image with preview
  - Set employee status (Active / Inactive)
- After filling in required fields, the user clicks **Submit**.
- The employee data is saved and reflected on the Dashboard.

---

## ▶️ Steps to Run the Project Locally

### ✅ Prerequisites
- Node.js (v16 or above)
- npm or yarn

### ▶️ Installation & Run
```bash
npm install
npm run dev
