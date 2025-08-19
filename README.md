# 🏨 HotelTrack Frontend

A responsive web application for hotel management and automation.  
The frontend is built with **Angular**, designed to consume the REST API.

---

## 🚀 Technologies
- **Angular** — frontend framework
- **HTML5 + CSS3** — responsive design
- **REST API** — integration with backend

---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Danillkerr/hotel-track-frontend.git
   cd hotel-track-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the server:
   ```bash
   npm start
   ```

---

## 📂 Project Structure

```bash
/src
 ├── app/
 │    ├── components/   # reusable UI components
 │    ├── pages/        # application pages
 │    ├── services/     # API communication
 │    ├── models/       # interfaces and types
 │    └── app.module.ts # root module
 └── assets/            # images, styles
```

---

## ✅ Features

- User authentication & registration
- Admin dashboard
- Room and booking management
- Guest information view
- Responsive design

---

## 📌 Commit Style

- **Format:**

  ```bash
  <type>[optional scope]: <description>

  [optional body]

  [optional footer(s)]
  ```

- **Types:**

  ```bash
   feat: - A new feature
   fix: - A bug fix
  ```
  Types other than fix: and feat: are allowed (build:, chore:, ci:, docs:, style:, refactor:, perf:, test:, and others.)

- **Example:**

  ```bash
  git commit -m "feat(auth): add auth by google"
  ```
