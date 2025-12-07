# 🚀 ELibrary – Backend API (Node.js + Express + MongoDB)

**ELibrary Backend** is the core server responsible for handling admin operations, book upload/delete, PDF storage, and communication with MongoDB Atlas.  
> ⚠️ **Note:** The hosted API is currently **stopped** due to hosting / free-tier limits (Render free tier exhausted).

---

## 🎯 Quick Links
| Platform | Status | Link |
|----------|--------|------|
| **Frontend** (Vercel) | 🔥 Active | [https://elibra.vercel.app/](https://elibra.vercel.app/) |
| **Backend API** (Render) | ⚡ Stopped | [https://api-elibrary.onrender.com](https://api-elibrary.onrender.com) |
| **Admin Dashboard** | 🔐 Secure | [Admin Login](https://elibra.vercel.app/) |

---

## 🧩 What this backend does

- Admin authentication (simple email/password)
- Upload books (PDF + metadata)
- Delete books  
- Store metadata in MongoDB Atlas  
- Serve JSON API + PDF URLs to frontend

---

## 📁 Project Structure
```bash
API-Elibrary/
├─ controllers/
├─ middleware/
├─ models/
├─ routes/
├─ uploads/
├─ server.js
├─ package.json
└─ .env
```

---

## ⚙️ Environment Variables (`.env`)

```bash
PORT=5000
MONGO_URI=your_mongo_atlas_uri

# Admin credentials
ADMIN_EMAIL=admin@example.com


# AWS S3 (if using)
AWS_ACCESS_KEY=your_aws_access_key
AWS_SECRET_KEY=your_aws_secret_key
AWS_BUCKET_NAME=your_bucket_name
AWS_REGION=your_region

```

# 💻 Local Setup
# 1. Clone repo
```bash
git clone https://github.com/codesbyharsh/API-Elibrary.git
cd API-Elibrary
```
# 2. Install dependencies
``` bash
npm install
```
# 3. Add .env file (use the template above)
```bash
Create a .env file in the root directory of the project.

Add the required environment variables inside it.

Sample .env file is provided in the code.
```
# 4. Start backend
```bash
npm start or nodemon server.js
```
Runs on → http://localhost:5000



---
### 🙌 Thanks for Checking Out ELibrary Backend — built as a learning full-stack project covering:
``` bash
- REST API Architecture
- Admin/Protected Routes
- File Upload Handling
- Cloud Storage (S3/Cloudinary)
- MongoDB Atlas Integration
- Hosting on Render
```
---

**If you want to collaborate, improve this project, or discuss ideas, feel free to connect!**

📧 Email: jadhavh655@gmail.com

💼 GitHub: https://github.com/codesbyharsh

🌐 [Portfolio](https://portfolio-harshal-jadhav.vercel.app/)

---

## ⭐ If you liked this project, don’t forget to star the repository!