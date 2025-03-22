# JOB-PORTAL-WEBSITE-main
 Job Portal
# Job portal - Full Stack Job Portal Website 🌐

## 💡 Description
**Job Portal** is a robust MERN Stack job portal that allows users to browse job listings, post job opportunities, and apply for jobs seamlessly. The platform features **secure authentication**, including email/password and **Google login via Firebase Authentication**. Users can filter job listings by title, location, and posting time, ensuring efficient job discovery. The system also includes **job management features**, **pagination**, and a sleek, responsive UI, making job searching and management effortless.

---

## 🚀 Features
### 👤 User Features
- 🔑 **Login:** Secure access via email/password authentication.
- 📧 **Google Login:** One-click login via Firebase Authentication.
- 📝 **Signup:** Quick registration using an email and password.
- 🍽️ **Job Listings:** Browse a wide range of job opportunities with details like title, location, and descriptions.
- 🔍 **Job Filters:** Refine job searches by **title, location, and posting time**.
- 💼 **Post & Manage Listings:** Users can create, edit, and manage their own job postings.
- 🗂️ **Pagination:** Well-organized job listings with pagination for a smooth browsing experience.

### 🧑‍💼 Admin Features
- 🔑 **Admin Login:** Access to an **admin panel** for managing the platform.
- 📝 **Job Management:** Admins can **update, delete, and manage** job postings.
- 👥 **User Management:** Monitor registered users and manage queries.
- 🛠️ **Content Moderation:** Ensure all job posts comply with platform guidelines.
- 📊 **Analytics & Reporting:** Generate reports on platform usage and job applications.

### 💡 Key Features
- 🔒 **Secure Authentication:** Users log in with **email/password** or **Google authentication**.
- 📑 **Detailed Job Information:** Job posts include descriptions, requirements, and employer details.
- 🎯 **Job Search Filters:** Filter job listings based on specific criteria.
- 🧭 **Easy Navigation:** Pagination ensures a seamless browsing experience.
- 📱 **Mobile-Friendly UI:** Fully responsive design for all devices.

---

## 🎯 Ideal For
- 👨‍💼 **Job Seekers:** Find and apply for jobs effortlessly.
- 🏢 **Employers & Recruiters:** Post and manage job listings.
- 🧑‍💼 **Admins:** Oversee the job portal’s users and content.
- 🌍 **General Users:** Anyone looking for job opportunities or to hire talent.

---

## ⚙️ Technologies Used
### **Frontend:**
- ⚛️ **React.js**
- 🎨 **CSS3**
- 💻 **Bootstrap**
- ⚙️ **JavaScript**
- 🧑‍💻 **Axios** (for API calls)

### **Backend:**
- 🖥️ **Node.js**
- 🖧 **Express.js**

### **Database:**
- 🗄️ **MongoDB** (NoSQL Database)

### **Authentication:**
- 🔐 **Firebase Authentication** (Google login)

---

## 🛠 Required Dependencies
Before running the application, install the following dependencies:

### **Backend Dependencies**
```sh
npm install express mongoose dotenv cors bcryptjs jsonwebtoken nodemon
```

### **Frontend Dependencies**
```sh
npm install react react-dom react-router-dom axios bootstrap
```

### **Tailwind CSS (Frontend UI Framework)**
```sh
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### **Firebase (Authentication & Hosting)**
```sh
npm install firebase
```

---

## ⚙️ How to Run

### **1️⃣ Change Directory:**
```sh
cd Folder location
```

### **2️⃣ Backend Setup:**
```sh
cd backend
npm install
```

### **3️⃣ Frontend Setup:**
```sh
cd ../frontend
npm install
```

### **4️⃣ Environment Variables Configuration:**
Create a `.env` file in both `backend` and `frontend` directories and set up the required environment variables.

#### **Backend (.env file)**
```sh
PORT=5000
MONGO_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_jwt_secret>
```

#### **Frontend (.env file)**
```sh
REACT_APP_FIREBASE_API_KEY=<your_firebase_api_key>
REACT_APP_FIREBASE_AUTH_DOMAIN=<your_firebase_auth_domain>
REACT_APP_FIREBASE_PROJECT_ID=<your_firebase_project_id>
REACT_APP_FIREBASE_STORAGE_BUCKET=<your_firebase_storage_bucket>
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=<your_firebase_messaging_sender_id>
REACT_APP_FIREBASE_APP_ID=<your_firebase_app_id>
```

### **5️⃣ Run the Application:**
#### **Start Backend Server:**
```sh
cd backend
npm start
```

#### **Start Frontend Server:**
```sh
cd frontend
npm start
```

### **6️⃣ Open the Application:**
Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📜 License
This project is open-source and available under the **MIT License**.

---

