# Recipe Sharing App

This app lets users post and search for cooking recipes...

---
# 🍽️ Recipe Sharing App (MERN Stack)

A full-stack recipe sharing platform where users can upload, search, and interact with recipes. Built with React, Node.js, Express, and MongoDB.

---

## 🌐 Live URLs

- 🔗 **Frontend**: [https://recipesharinapp.netlify.app/]
- 🔗 **Backend API**: [https://recipe-sharing-app-eqri.onrender.com]

---

## 🛠️ Tech Stack

| Layer     | Technology              |
|-----------|--------------------------|
| Frontend  | React + Vite + Tailwind |
| Backend   | Node.js + Express + mongodb      |
| Database  | MongoDB Atlas           |
| Auth      | JWT                     |
| CI/CD     | Netlify (frontend), Render (backend) |
| Deployment Monitoring | Netlify & Render Logs |
| Hosting   | Netlify + Render        |

---

## 📸 Screenshots

### 🟢 Netlify (Frontend CI/CD)

> When code is pushed to the `main` branch, Netlify triggers an auto-deploy.

[<img width="883" height="407" alt="image" src="https://github.com/user-attachments/assets/a962d43e-d7f7-46f5-965a-2641a028a1f3" />]


---

### 🔵 Render (Backend CI/CD)

> Render automatically rebuilds and redeploys the backend when changes are pushed.

![<img width="709" height="364" alt="image" src="https://github.com/user-attachments/assets/4ba63f39-fee9-41a4-9aad-1a4abd7f772a" />
]
![<img width="624" height="364" alt="image" src="https://github.com/user-attachments/assets/edfeb763-b60b-42cc-b36d-77d6f4f920cc" />
]
![<img width="688" height="280" alt="image" src="https://github.com/user-attachments/assets/8acdd69a-09b6-4814-8198-51f4aa767651" />
]
---

## 🚀 Deployment Instructions

### 🔧 Backend (Render)

1. **Push Backend to GitHub**
2. Go to [https://render.com](https://render.com) → “New Web Service”
3. Connect GitHub repo
4. Fill in:
   - **Build Command**:  
     ```
     pnpm install
     ```
   - **Start Command**:  
     ```
     pnpm run build
     ```
   - **Environment Variables**:
     - `MONGO_URI`: mongodb+srv://munyaopatrick:V1KrPcqr0BqQMkgz@cluster0.8gno6sv.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
     - `JWT_SECRET`: V1KrPcqr0BqQMkgz

5. Deploy!

---

### 🎯 Frontend (Netlify)

1. **Frontend Folder**: `/client`
2. Create `.env` in `client/`:

```env
VITE_API_URL=https://recipe-sharing-app-eqri.onrender.com/api

