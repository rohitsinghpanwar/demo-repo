# GitHub Webhook Demo

This project demonstrates capturing GitHub events (Push, Pull Request, Merge) via webhooks, storing them in MongoDB, and displaying them in a clean UI using React. The backend is built using Flask. 

---

## 🔧 Tech Stack
## random changes
- **Frontend:** React (Vite) 
- **Backend:** Flask (Python)
- **Database:** MongoDB (Atlas or local)
- **Tunneling:** ngrok (for webhook testing)

---

## 📦 Repositories

- 🔁 **Webhook Receiver & UI:** [webhook-repo](https://github.com/your-username/webhook-repo)
- 🚀 **Trigger Repo (for push/PR/merge actions):** [action-repo](https://github.com/your-username/action-repo)

---

## 📌 Features

- Receives GitHub Webhook events:
  - `push`
  - `pull_request`
  - `merge` (from merged PRs)
- Stores only essential data in MongoDB
- Displays actions in a minimal UI
- Polls for updates every 15 seconds

---


