# LesonPaw - Online Learning Platform

![LesonPaw Logo](public/logo.png)

---

## 🌐 Live Website
[Visit LesonPaw](https://lesonpaw.web.app)

---

## 📝 Description
**LesonPaw** is a comprehensive online learning platform designed to connect students with professional tutors across Haiti. Our platform offers flexible learning options, supporting both **in-person and virtual sessions** across a wide range of subjects. With **multi-language support**, LesonPaw makes quality education accessible to everyone.

---

## ✨ Key Features

LesonPaw offers tailored functionalities for students, teachers, and administrators to ensure a seamless and effective learning experience.

### 🎯 For Students
* **Smart Teacher Search**: Easily find the perfect tutor by filtering based on subject, availability, and preferred learning style.
* **Booking Management**: Conveniently book and manage all your learning sessions in one place.
* **Job Posting**: Post custom learning requests to find tutors who can meet your specific needs.
* **Progress Tracking**: Monitor your achievements and milestones to stay motivated.
* **Multi-language Support**: Access the platform in English, French, Spanish, and Haitian Creole.

### 👨‍🏫 For Teachers
* **Profile Management**: Showcase your expertise, qualifications, and the services you offer.
* **Service Management**: Add, edit, or remove your teaching services with ease.
* **Job Applications**: Browse student-posted jobs and apply to those that match your skills.
* **Schedule Management**: Manage your teaching calendar and availability.
* **Payment Integration**: Receive secure payments for your sessions directly through the platform.

### 👑 For Administrators
* **User Management**: Gain full control over all user roles, permissions, and accounts.
* **Application Review**: Efficiently approve or reject tutor applications.
* **Content Management**: Manage blog posts and success stories on the platform.
* **Analytics Dashboard**: Monitor key platform performance metrics and user engagement.
* **Payment Oversight**: Oversee all financial transactions and payment processes.

---

## 🛠️ Tech Stack

LesonPaw is built with a robust and modern technology stack to ensure performance, scalability, and a great user experience.

### Frontend
* ⚛️ **React.js** (with Vite): For a fast, responsive, and component-based user interface.
* 🎨 **Tailwind CSS**: For utility-first CSS styling and rapid UI development.
* 🎞️ **Framer Motion**: For smooth and engaging animations.
* 🔁 **React Query**: For efficient data fetching, caching, and state management.
* 🌐 **React Router**: For declarative routing within the application.
* 🌍 **i18n**: For comprehensive multi-language support.

### Backend
* 🧩 **Node.js + Express.js**: For a powerful and scalable server-side environment.
* 💾 **MongoDB**: As the flexible NoSQL database for data storage.
* 🔐 **Firebase Authentication + JWT**: For secure user authentication and authorization.
* 📡 **Axios**: For making efficient HTTP requests to the backend API.

---

## 🗺️ Route Structure

LesonPaw features a well-defined route structure to manage different user experiences and access levels.

### 🔓 Public Routes
* `/` – Home Page
* `/about` – About Us
* `/contact` – Contact Information
* `/blogs` – Blog Posts
* `/find-teacher` – Search for Tutors
* `/become-teacher` – Teacher Registration
* `/login` & `/signup` – User Authentication

### 🧑‍🎓 Student Dashboard
* `/dashboard/studentProfile`
* `/dashboard/my-bookings`
* `/dashboard/joinTeacher`
* `/dashboard/post-job`
* `/dashboard/myJobs`

### 👨‍🏫 Teacher Dashboard
* `/dashboard/teacherProfile`
* `/dashboard/tutor-jobs`
* `/dashboard/manage-services`

### 👮‍♂️ Admin Dashboard
* `/dashboard/manage-users`
* `/dashboard/tutors`
* `/dashboard/message`
* `/dashboard/add-tutor`
* `/dashboard/teacher-applications`
* `/dashboard/manage-payments`
* `/dashboard/admin-analytics`
* `/dashboard/students`
* `/dashboard/all-jobs`
* `/dashboard/service`
* `/dashboard/story`
* `/dashboard/confirmation`
* `/dashboard/addBlog`
* `/dashboard/editBlog`

---

## 🎨 UI & Design Features

LesonPaw's design focuses on user experience, combining modern aesthetics with intuitive navigation.

* ✅ **Responsive Design**: Optimized for seamless viewing across all devices (desktops, tablets, and mobile).
* 🧼 **Modern & Clean UI**: A consistent and visually appealing user interface.
* 🎯 **Brand Colors**:
    * Primary Blue: `#005482`
    * Cyan Blue: `#70C5D7`
    * Bright Pink: `#DA3A60`
    * Yellow/Orange: `#FCBB45`
    * White: `#FFFFFF`
* 🔄 **Smooth Transitions**: Engaging animations and smooth transitions for a dynamic feel.
* 🧭 **Intuitive Navigation**: Easy-to-use and accessible navigation for all users.

---

## 🚀 Getting Started

To get LesonPaw up and running on your local machine, follow these steps:

### 📋 Prerequisites
Ensure you have the following installed:
* **Node.js** v14+
* **npm** or **yarn**
* **MongoDB** (running locally or a cloud instance)
* **Firebase account** (for authentication and environment variables)

### 🧪 Demo Credentials (Admin)
For demonstration purposes, you can use the following admin credentials:

* **Email**: `yusufoesta5t@gmail.com`
* **Password**: `Fa@1234`

> **Note**: Please use these credentials responsibly and for demonstration purposes only.

### Installation
1.  **Clone the repositories**:
    ```bash
    git clone [https://github.com/Rayhan-50/Lesson-paw](https://github.com/Rayhan-50/Lesson-paw) # Frontend
    git clone [https://github.com/Rayhan-50/Lesson-paw-server](https://github.com/Rayhan-50/Lesson-paw-server) # Backend
    ```
2.  **Navigate to the frontend directory**:
    ```bash
    cd Lesson-paw
    ```
3.  **Install frontend dependencies**:
    ```bash
    npm install
    # or
    yarn install
    ```
4.  **Set up frontend environment variables**: Create a `.env` file in the `Lesson-paw` directory and add your Firebase configuration:
    ```env
    VITE_API_KEY=your_firebase_api_key
    VITE_AUTH_DOMAIN=your_firebase_auth_domain
    VITE_PROJECT_ID=your_firebase_project_id
    VITE_STORAGE_BUCKET=your_firebase_storage_bucket
    VITE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
    VITE_APP_ID=your_firebase_app_id
    ```
5.  **Run the frontend development server**:
    ```bash
    npm run dev
    # or
    yarn dev
    ```
    This will start the frontend application, usually on `http://localhost:5173` or similar.

6.  **Navigate to the backend directory**:
    ```bash
    cd ../Lesson-paw-server
    ```
7.  **Install backend dependencies**:
    ```bash
    npm install
    # or
    yarn install
    ```
8.  **Set up backend environment variables**: Create a `.env` file in the `Lesson-paw-server` directory and add your MongoDB URI, JWT secret, and any other necessary keys.
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    # Add other environment variables as needed (e.g., Stripe keys if implemented)
    ```
9.  **Run the backend server**:
    ```bash
    npm start
    # or
    yarn start
    ```
    This will start the backend API, usually on `http://localhost:5000` or similar.

---

## 👨‍💻 Developer Credits

LesonPaw is a collaborative effort by two talented full-stack developers.

### Yusuf Faisal
* **Role**: Lead Full-Stack Developer, UI/UX Designer & System Architect
* **Portfolio**: [yusuf-faisal.netlify.app](https://yusuf-faisal.netlify.app)
* **GitHub**: [@yusufoesta](https://github.com/yusufoesta)
* **Specializations**:
    * **Frontend**: React.js Development, Responsive Design, User Experience, Component Architecture, State Management, Multi-language Implementation.
    * **Backend**: Node.js & Express.js, MongoDB Database Design, RESTful API Development, Authentication Systems, Server Architecture, Security Implementation.

### Rayhan Ahmed
* **Role**: Lead Full-Stack Developer, System Architect & UI/UX Designer
* **Portfolio**: [adhesive-bed.surge.sh](https://adhesive-bed.surge.sh)
* **GitHub**: [@rayhan](https://github.com/rayhan)
* **Specializations**:
    * **Frontend**: React.js Development, Modern UI/UX Design, Component Development, State Management, Animation & Interactions, Progressive Web Apps.
    * **Backend**: API Development, Database Architecture, Authentication Systems, Payment Integration, Server Optimization, Cloud Infrastructure.

Both developers have made significant contributions across all aspects of the project, showcasing their expertise in full-stack development, system architecture, and modern web technologies.

---
© 2024 LesonPaw. All Rights Reserved.