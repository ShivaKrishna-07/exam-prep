# 🎓 Prep — Academic Resource Platform for College Students

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/75a0ce53-c3a5-4882-afdc-6677e7701920" />


## 🚀 Project Overview

**Prep** is an academic support platform built for college students to simplify exam preparation.  
It provides **subject-wise notes, previous year question papers (PYQs), syllabus, curated video resources, and AI-powered analysis** to identify important and frequently repeated questions.

The platform aims to reduce scattered resources and bring everything under **one centralized learning system**.

## ✨ Key Highlights

- 📚 Centralized academic resources (syllabus, notes, PYQs)
- 🎥 100+ curated YouTube videos per subject
- 📂 Seamless PDF access via **Google Drive API**
- 🤖 AI-powered chatbot for student queries
- 🧠 Smart modal to analyze PYQs and highlight **important & repeated questions**
- 🎨 Clean, student-friendly UI
- 🚀 Scalable & production-ready architecture

## 🛠️ Tech Stack

### Frontend
- **Next.js**
- **Tailwind CSS**
- **TypeScript**

### Backend
- **Next.js API Routes**
- **Node.js**

### Database & APIs
- **MongoDB**
- **Google Drive API**


## Setup Instructions 💻

### 1. Clone the repository

```shell
git clone https://github.com/ShivaKrishna-07/prep.git
cd prep
```

### 2. Install Dependencies

```shell
npm install
```

### 3. Setup .env file

```js
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...

# Database
MONGODB_URI=...

# AI Configuration
NEXT_PUBLIC_GEMINI_API_KEY=...

# Google Drive API
ROOT_FOLDER_ID=...
CLIENT_EMAIL=...
PRIVATE_KEY=...
GOOGLE_CLOUD_CREDENTIALS=...

# Environment
NODE_ENV=development
```

### 4. Build the App 🔨

```shell
npm run build
```

### 5. Start the App 🚀

```shell
npm start
```


