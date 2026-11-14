# ✅ MERN Task Planner

A full-stack task manager: users sign up, create tasks with descriptions, groups and images, and move them between **active** and **completed**.

## Features
- 🔐 Sign up and log in
- ➕ Add tasks with name, description, group and image
- ✏️ Edit and delete tasks
- ✔️ Mark tasks as completed and view active vs completed lists
- 👤 Profile page
- 🔔 Toast notifications

## Tech stack
**Frontend:** React · React Router · Material UI · React Bootstrap · Axios · React Toastify
**Backend:** Node.js · Express · MongoDB · Mongoose

## Project structure
```
client/   React frontend
server/   Express REST API (users & tasks)
```

## Run locally
```bash
git clone https://github.com/saravanan-22/task-planner-mern.git
cd task-planner-mern

# backend
cd server && npm install
cp .env.example .env   # then add your MongoDB URI
npm start

# frontend (new terminal)
cd client && npm install && npm start
```

## License
[MIT](LICENSE) © Saravanan
