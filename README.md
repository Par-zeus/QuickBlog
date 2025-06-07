# QuickBlog

A full-stack, feature-rich blogging platform with a modern admin dashboard, rich text editing, comment moderation, and secure authentication. Built with **React**, **Node.js**, **Express**, and **MongoDB**.

---

## 🚀 Features

- **Rich Text Blog Editor:**  
  Create and edit blogs with advanced formatting using Quill.
- **Image Upload & Optimization:**  
  Upload images with automatic optimization via ImageKit.
- **Admin Dashboard:**  
  Secure dashboard for managing blogs, comments, and analytics.
- **Comment Moderation:**  
  Approve or delete comments before they appear publicly.
- **JWT Authentication:**  
  Secure admin login and protected routes.
- **Responsive UI:**  
  Mobile-friendly design using Tailwind CSS.
- **RESTful API:**  
  Clean separation of user and admin endpoints.
- **Deployment Ready:**  
  Easily deployable on Vercel or any Node.js hosting.

---

## 🛠️ Tech Stack

- **Frontend:** React, Tailwind CSS, Quill, Axios, React Hot Toast
- **Backend:** Node.js, Express, MongoDB, Mongoose, JWT
- **Image Handling:** ImageKit
- **Deployment:** Vercel (Frontend), Any Node.js host (Backend)

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/quickblog.git
cd quickblog
```

### 2. Install dependencies

#### Backend
```bash
cd server
npm install
```

#### Frontend
```bash
cd ../client
npm install
```

### 3. Environment Variables

#### Backend (`server/.env`)
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

#### Frontend (`client/.env`)
```
REACT_APP_API_URL=http://localhost:3000/
```

### 4. Run the project

#### Backend
```bash
cd server
npm run dev
```

#### Frontend
```bash
cd client
npm start
```

---

## 🌐 API Endpoints

### **Public**
- `GET /api/blog/all` — Get all blogs
- `GET /api/blog/:blogId` — Get a single blog
- `POST /api/blog/comments` — Get comments for a blog
- `POST /api/blog/add-comment` — Add a comment

### **Admin (Protected)**
- `POST /api/admin/login` — Admin login
- `GET /api/admin/blogs` — Get all blogs
- `GET /api/admin/comments` — Get all comments
- `POST /api/admin/delete-comment` — Delete a comment
- `POST /api/admin/approve-comment` — Approve a comment
- `GET /api/admin/dashboard` — Dashboard analytics

---

## ✨ Unique Highlights

- **Rich Text Editing:**  
  Seamless blog creation with Quill, supporting images and formatting.
- **Image Optimization:**  
  Automatic image compression and conversion to modern formats.
- **Admin-Only Operations:**  
  Secure, role-based access for all admin features.
- **Real-Time Moderation:**  
  Instantly approve or delete comments with UI feedback.
- **Production-Ready:**  
  Handles case-sensitive imports for smooth deployment on Linux/Vercel.

---

## 🖥️ Screenshots
![image](https://github.com/user-attachments/assets/98631b36-489a-4589-9b18-7dca1bd95018)
![image](https://github.com/user-attachments/assets/1b1c78cd-df2a-4db1-bf31-5a66b0e3f027)
![image](https://github.com/user-attachments/assets/49471443-3ddc-4381-80b7-393b7ae96ef3)

## Not Approved Comments
![image](https://github.com/user-attachments/assets/cc7f852b-bf76-4f9c-ba85-e54be419780c)
## Approved Comments
![image](https://github.com/user-attachments/assets/9673f7c8-18b0-4d47-a241-6f0b99afec45)


> _Add screenshots of your dashboard, blog editor, and comment moderation UI here._

---

## 📝 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📧 Contact

For questions or support, contact [dasparthhh24@gmail.com](mailto:dasparthhh24@gmail.com)

---

**Happy Blogging! 🚀**
