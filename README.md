# 🩺 Doctor Appointment Booking System (MERN Stack)

A full-featured Doctor Appointment Booking System built using the **MERN stack** and **React + Vite**, with support for Razorpay payments, Cloudinary media upload, and multi-role dashboards. Users can book appointments with doctors, make payments, and manage their appointments. Doctors can manage their schedule and profile, while Admins can manage doctors and oversee the platform.

---

## 🌐 Deployed Links

**Client Link:** https://doctor-appointment-frontend-indol.vercel.app/

**Admin Portal:** https://doctor-appointment-admin-chi.vercel.app/

---

## 🚀 Features

### For Users (Patients):
✅ Signup / Login with secure authentication  
✅ Browse doctors by specialties  
✅ Book appointments with available doctors  
✅ Pay consultation fees online or in cash  
✅ View and cancel existing appointments  
✅ Update personal profile information  

### For Doctors:
✅ Login to doctor dashboard  
✅ Manage their upcoming appointments  
✅ Update doctor profile information  
✅ Manage availability status to accept or block bookings  

### For Admin:
✅ Login to admin panel  
✅ Add doctors  
✅ View and manage appointments and users  
✅ Full platform control  

---

## 🛠 Tech Stack

**Frontend:** React + Vite, Tailwind CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB with Mongoose  
**Authentication:** JWT  
**Payments:** Razorpay  
**Media Uploads:** Cloudinary  
**Deployment:** Vercel  

---

## 🏗 Folder Structure

```
doctor-booking-app/
├── frontend/       # User panel (React + Vite)
├── admin/          # Admin panel (React + Vite)
├── backend/        # Server (Node.js + Express)
└── README.md
```

---

## 📦 Setup & Installation

### Prerequisites:
- Node.js (Latest LTS)
- MongoDB
- npm or yarn

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/omrajkamat68/Doctor_Appointment_Bookin_System.git
cd Doctor_Appointment_Bookin_System
```

---

### 2️⃣ Install Dependencies

```bash
# Install frontend dependencies
cd frontend
npm install

# Install admin panel dependencies
cd ../admin
npm install

# Install backend dependencies
cd ../backend
npm install
```

---

### 3️⃣ Set up Environment Variables

Create `.env` files in all three folders: `frontend`, `admin`, and `backend`.

#### Example for `frontend/.env`:
```env
VITE_BACKEND_URL=
VITE_RAZORPAY_KEY_ID=
```

#### Example for `admin/.env`:
```env
VITE_BACKEND_URL=
```

#### Example for `backend/.env`:
```env
MONGODB_URI=
CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_SECRET_KEY=
ADMIN_EMAIL=admin@prescripto.com
ADMIN_PASSWORD=medadmin@12,3#
JWT_SECRET=
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=
CURRENCY=
```

---

### 4️⃣ Start the Development Servers

```bash
# Run backend
cd backend
npm run server

# Run frontend (user panel)
cd ../frontend
npm run dev

# Run admin panel
cd ../admin
npm run dev
```

---

## 💳 Payment Integration

- Users can pay consultation fees via **Razorpay**
- Option to pay in **Cash** is also available

---

## 🖼 Media Upload

- Doctor and User profile pictures are uploaded using **Cloudinary**

---

## 🔐 Authentication

- Role-based JWT authentication implemented for:
  - Users
  - Doctors
  - Admin

---

