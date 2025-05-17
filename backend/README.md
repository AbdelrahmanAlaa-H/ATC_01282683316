# 🎯 Backend 🎯 

---

## 🚀 Deployment

The backend API is deployed and live at:

[https://event-booking-system-production-b9f0.up.railway.app](https://event-booking-system-production-b9f0.up.railway.app)

We used **Railway** platform for hosting and continuous deployment, which provides an easy way to deploy Node.js apps connected to MongoDB Atlas.

---

## ⚙️ Features

- 🔐 User Authentication (Register/Login with JWT)
- 🗂️ Role-based Access (Admin & User)
- 📆 CRUD Operations for Events (Admin only)
- 📥 Book Events
- 🖼️ Event Image Upload using Cloudinary
- 🏷️ Event Categories & Tags
- 📃 Swagger API Documentation

---

## 📦 Installation & Setup

1. **Clone the Repository**

```bash
git clone https://github.com/AbdelrahmanAlaa-H/ATC_01282683316.git
cd ATC_01282683316/backend
```

2. **Install Dependencies**

```bash
npm install
```

3. **Environment Variables**

- Create a `.env` file in the root directory based on `.env.example`

```env
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

4. **Run the Server**

```bash
npm run dev
```

---

## 🔌 API Routes

- `POST /api/auth/register` - Register user
- `POST /api/auth/login` - Login user
- `GET /api/events` - Get all events
- `POST /api/events` - Create event (Admin)
- `PUT /api/events/:id` - Update event (Admin)
- `DELETE /api/events/:id` - Delete event (Admin)
- `POST /api/bookings/:eventId` - Book event (User)

---

## 📄 Documentation

You can access the full API documentation via Swagger once the server is running:

---

## 🔑 Default Admin Credentials

To access the admin panel and manage events, use the following default admin account:

- **Email:** `admin@example.com`
- **Password:** `123456`

You can access the admin panel live here:  
[https://event-booking-system-frontend.vercel.app/](https://event-booking-system-frontend.vercel.app/)

---

## 📬 Contact

For questions or support, feel free to reach out via GitHub issues or email me directly at:  
**abdelrhmanalaa512@gmail.com**

Don't hesitate to contact me anytime!

---
