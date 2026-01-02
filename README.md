# 🏥 Appointy – Doctor Appointment Web Application

**Appointy** is a full-stack doctor appointment platform built using the **MERN stack**, designed to simplify healthcare access through online appointment booking, role-based dashboards, and secure payments. The application supports **Patients**, **Doctors**, and **Admins**, each with dedicated features and workflows.

---

## 🚀 Tech Stack

- **Frontend:** React.js (Vite)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Payments:** Razorpay
- **API Communication:** Axios

---

## 🔐 Role-Based Access Control

### 👤 Patient
- Sign up and log in securely  
- Search doctors by specialization  
- Book, reschedule, or cancel appointments  
- Make payments using cash or Razorpay  
- Manage personal profile and appointment history  

---

### 🩺 Doctor
- Access a personalized dashboard  
- View and manage patient appointments  
- Track earnings and appointment statistics  
- Update profile details such as fees, availability, and description  

---

### 🛠️ Admin
- Platform-wide dashboard with analytics  
- Add and manage doctor profiles  
- View and control all appointments  
- Cancel or mark appointments as completed  

---

## 🖥️ Application Pages

### 🏠 Home
- Doctor search by specialty  
- Featured doctors section  
- Informational pages (About, Privacy Policy, Contact)  

### 🩺 Doctors Listing
- Displays all registered doctors  
- Filter doctors by specialization  
- Navigate to detailed booking page  

### 📅 Appointment Booking
- Doctor profile with experience and qualifications  
- Date & time slot selection  
- Payment method selection  
- Login required before booking  

### 👤 User Profile
- Update personal details and profile image  
- View upcoming and past appointments  
- Secure logout  

---

## 📊 Dashboards

### Admin Dashboard
- Total doctors, patients, and appointments  
- Add/edit/delete doctor profiles  
- Appointment management  

### Doctor Dashboard
- Earnings overview  
- Appointment list with patient details  
- Appointment status updates  

---

## 💳 Payment Integration

- Supports **Cash Payment**
- Integrated **Razorpay** for secure online transactions
- Payment details linked with appointment records

---

## ⚙️ Local Setup Instructions

### 1️⃣ Clone Repository
   ```bash
   git clone https://github.com/your-username/appointy.git
   cd appointy

2. **Install Dependencies**:
   ```bash
   npm install
   cd client
   npm install
   ```

3. **Environment Variables**:
   - Create a `.env` file in the root directory and add the following:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     STRIPE_API_KEY=your_stripe_api_key
     RAZORPAY_API_KEY=your_razorpay_api_key
     ```

4. **Run the Application**:
   ```bash
   npm run dev
   ```

## 📦 Folder Structure

```plaintext
appointy/
├── client/          # Frontend (React.js)
├── server/          # Backend (Node.js, Express.js)
├── models/          # MongoDB Schemas
├── controllers/     # API Controllers
├── routes/          # API Routes
├── middleware/      # Authentication and Error Handling
├── config/          # Configuration Files
├── utils/           # Utility Functions
├── public/          # Static Files
└── .env             # Environment Variables
```

## 🤝 Contributions

Contributions are welcome!
Feel free to open issues or submit pull requests to improve the project.


## 🌟 Acknowledgements

- Thanks to the open-source communities behind MongoDB, Express, React, Node.js, and Razorpay for their powerful tools and libraries.

---
