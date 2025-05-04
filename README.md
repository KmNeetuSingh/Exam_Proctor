
# 🧠 Exam Tutor – Full Stack Application

A full-stack exam management system built with:

- **Backend:** Node.js, Express, MongoDB
- **Frontend:** TypeScript + Vite (No React)
- **Authentication:** JWT
- **Styling:** Tailwind CSS

---

## 📁 Project Structure

```
.
├── backend         # Express + MongoDB API
├── frontend        # Vite + TypeScript (no React)
```

---

## ⚙️ Backend Setup (`/backend`)

### 1. Navigate to the backend folder:

```bash
cd backend
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Create a `.env` file in `/backend`:

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/Examtutor
JWT_SECRET=your_secret_key
```

### 4. Start the server:

```bash
npm run dev
```

The backend API will run at: `http://localhost:5000`

---

## 🌐 Frontend Setup (`/frontend`)

### 1. Navigate to the frontend folder:

```bash
cd frontend
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Create a `.env` file in `/frontend`:

```env
VITE_API_BASE_URL=http://localhost:5000
```

### 4. Start the frontend server:

```bash
npm run dev
```

Visit the app at: `http://localhost:5173`

---

## 📸 Profile Picture Handling

Uploaded profile pictures are stored at:

```
/backend/uploads/profile-pics
```

They are served statically through Express and displayed using:

```ts
${VITE_API_BASE_URL}/uploads/profile-pics/filename.jpg
```

---

## 📦 Features

- ✅ User authentication (Student/Admin)
- ✅ Exam creation and listing
- ✅ Profile picture uploads
- ✅ Protected routes
- ✅ Dark/light mode toggle

---

## 🧪 Tech Stack

### Backend:

- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer (for file uploads)
- JWT (Authentication)

### Frontend:

- TypeScript
- Vite
- Tailwind CSS
- Vanilla JavaScript (no frameworks)

---

## 📸 Screens & Comparisons

### 🔹 Home Screen – Initial View

![Home Screen](./screenshots/9bd7358b-a2c0-4786-9c63-72e79e2f2ae2.png)

---

### 🔹 Navigation/Content Layout

![Navigation View](./screenshots/09913b7e-5f1b-47c3-98e5-33621cc66070.png)

---

### 🔹 Table/List View Comparison

![List/Table View 1](./screenshots/0c06cb1d-9e3d-4485-a846-f2e48a5c792b.png)

![List/Table View 2](./screenshots/4bbb07e8-f693-41c0-8970-3566b6547001.png)

---

### 🔹 Settings or Details View

![Details View](./screenshots/741dac13-405d-454c-b6fe-ac0aa87ad91f.png)

---

### 🔹 Pop-up / Modal / Notification State

![Modal View](./screenshots/5d8e1474-34f9-4dc3-bcc9-19c2f95c1789.png)

---

### 🔹 Dark Mode or Alternate Theme

![Theme or Alternate UI](./screenshots/4c35ee07-12fb-4b86-8b4c-ea1402f825dd.png)

---

### 🔹 Final Screen – Summary or Overview

![Final Summary Screen](./screenshots/e6262b28-9b60-43ff-ae1e-fb7555fafcd6.png)
