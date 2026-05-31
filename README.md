# Task Manager App 🧩

A modern React + TypeScript + Vite project for managing teams, projects, tasks, and users.
This app includes authentication, role-based access, project dashboards, task boards, deadline alerts, and local persistence using Redux Toolkit and localStorage.

## 📌 App Overview

Task Manager is a collaborative productivity dashboard built with a clean UI and practical workflows.
It helps teams track projects from kickoff to completion while managing tasks by status, priority, assignee, and deadline.

The app includes:
- Secure login and registration
- Admin-only project creation and user management
- Project cards with task analytics
- Task boards with filters, status updates, and deadline notifications
- Local data persistence in browser storage

## ✨ Key Features

- **User Authentication**: Login and register users with validation.
- **Role-Based Access**: Admin users can create projects and manage users.
- **Projects Dashboard**: View active projects and project summaries.
- **Task Management**: Create, edit, delete, and update task status.
- **Filtering & Search**: Filter tasks by title, status, priority, assignee, and due date.
- **Deadline Notifications**: Task deadline alerts via toast messages.
- **Analytics**: Visual task status breakdown with Recharts.
- **Persistence**: Project, task, and user data saved in localStorage.
- **Responsive UI**: Built with Tailwind CSS for a polished experience.

## 🚀 Technologies Used

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Redux Toolkit
- React Router v7
- React Hook Form
- React Toastify
- Recharts
- React DatePicker

## 🛠 Installation

```bash
pnpm install
pnpm dev
```

Then open the local Vite URL shown in the terminal.

## 🔑 Default Admin Account

Use the default admin credentials to access admin routes and management features:

- Email: `admin@gmail.com`
- Password: `123`

## 🧪 Notes

- Registered users are stored in `localStorage`.
- Admin routes are protected and only visible to users with the `admin` role.
- Tasks and projects are persisted between refreshes.

## 📂 Project Structure

- `src/components` — reusable UI components and types
- `src/pages` — page views for auth, projects, tasks, and user management
- `src/redux` — Redux store and slices for auth, projects, tasks, users
- `src/routes` — application routing and route guards
- `src/hooks` — custom hooks for deadline notification behavior

## 💡 Recommended Usage

1. Login with the default admin account.
2. Create a project from the dashboard.
3. Add tasks to a project with priority, assignee, deadline, and status.
4. Use filters to focus on urgent or overdue work.
5. Manage team members via the Users section.

---

Thank you for using Task Manager! 🎉
