# 🚀 Project Management System

A modern and scalable **Project Management System** designed to help teams efficiently create, manage, track, and monitor multiple projects and tasks from a centralized dashboard.

The system allows organizations and teams to manage projects, assign tasks, track progress, monitor deadlines, and collaborate efficiently — all from a single platform.

---

## 📌 Features

### 📊 Dashboard
- Overview of all projects and tasks
- Project progress tracking
- Task statistics
- Pending, completed, and in-progress tasks
- Quick access to recent projects
- Team activity overview

### 📁 Project Management
- Create and manage multiple projects
- Add project descriptions and details
- Set project start and end dates
- Track project status
- Monitor overall project progress
- View project-specific tasks

### ✅ Task Management
- Create tasks within projects
- Assign tasks to team members
- Set task priority
- Set deadlines
- Update task status
- Track task progress
- Manage pending and completed tasks

### 👥 Team Management
- Add team members
- Assign members to projects
- Assign tasks to specific users
- Manage user roles and permissions

### 🔐 Authentication & Authorization
- Secure login system
- Protected routes
- User authentication
- Role-based access control
- Permission-based actions

### 🔎 Search & Filtering
- Search projects
- Search tasks
- Filter tasks by status
- Filter by priority
- Filter by assigned member
- Sort project/task data

### 📈 Progress Tracking
- Track project completion percentage
- Monitor task completion
- Identify pending tasks
- Monitor project deadlines

---

## 🛠️ Tech Stack

### Frontend
- **Next.js**
- **React.js**
- **TypeScript**
- **Tailwind CSS**
- **shadcn/ui**
- **Lucide React**

### Backend
- REST APIs
- Node.js / Backend API

### Database
- MySQL / PostgreSQL

### Tools
- Git
- GitHub
- VS Code
- npm

---

## 🏗️ System Architecture

```text
                   ┌─────────────────────┐
                   │       User          │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │   Next.js Frontend  │
                   │ React + Tailwind    │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │      REST API       │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │      Database       │
                   │ MySQL / PostgreSQL  │
                   └─────────────────────┘
```

---

## 📂 Project Structure

```text
project-management/
│
├── app/
│   ├── dashboard/
│   ├── projects/
│   ├── tasks/
│   ├── users/
│   ├── profile/
│   ├── login/
│   └── layout.tsx
│
├── components/
│   ├── dashboard/
│   ├── projects/
│   ├── tasks/
│   ├── users/
│   ├── layout/
│   └── ui/
│
├── services/
│   ├── api.ts
│   ├── auth.service.ts
│   ├── project.service.ts
│   └── task.service.ts
│
├── hooks/
│
├── types/
│
├── utils/
│
├── public/
│
├── styles/
│
├── .env.local
├── package.json
├── tsconfig.json
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/project-management.git
```

### 2. Navigate to the Project

```bash
cd project-management
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```

Update the API URL according to your backend configuration.

### 5. Start the Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

## 🔑 User Roles

The system can support multiple roles such as:

| Role | Permissions |
|------|-------------|
| Admin | Manage users, projects, tasks and permissions |
| Project Manager | Create projects, assign tasks and monitor progress |
| Team Member | View assigned projects and update tasks |
| Viewer | View project and task information |

---

## 📋 Project Workflow

```text
Create Project
      ↓
Add Team Members
      ↓
Create Tasks
      ↓
Assign Tasks
      ↓
Set Priority & Deadline
      ↓
Track Progress
      ↓
Update Task Status
      ↓
Complete Project
```

---

## 📊 Task Status

Tasks can be managed using different statuses:

```text
TODO
  ↓
IN PROGRESS
  ↓
REVIEW
  ↓
COMPLETED
```

---

## 🎯 Main Use Case

This project is useful for organizations where **multiple projects and multiple tasks need to run simultaneously**.

Instead of managing tasks through spreadsheets, chats, or different tools, teams can use a centralized dashboard to:

- Manage multiple projects
- Assign tasks to different team members
- Track task progress
- Monitor deadlines
- Manage team responsibilities
- View project status
- Improve overall productivity

---

## 🔮 Future Enhancements

- Real-time notifications
- Email notifications
- Team chat
- File and document sharing
- Calendar integration
- Gantt charts
- Advanced analytics
- Activity timeline
- Real-time collaboration
- AI-powered task suggestions
- AI project summaries
- Automated task prioritization
- Docker deployment
- Cloud deployment

---

## 📸 Screenshots

### Dashboard

Add your dashboard screenshot here:

```markdown
![Dashboard](./screenshots/dashboard.png)
```

### Project Management

```markdown
![Projects](./screenshots/projects.png)
```

### Task Management

```markdown
![Tasks](./screenshots/tasks.png)
```

---

## 🔒 Security

The application is designed with security and access control in mind.

- Protected routes
- Authentication
- Role-based authorization
- Permission-based access
- Secure API communication
- Environment variables for sensitive configuration

---

## 🤝 Contribution

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/new-feature
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add new feature"
```

5. Push the branch

```bash
git push origin feature/new-feature
```

6. Create a Pull Request

---

## 👨‍💻 Author

**Abhi Gautam**

Full Stack Developer | React Developer | Next.js Developer

Interested in building scalable web applications and integrating AI into modern full-stack applications.

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is available for educational and development purposes.
