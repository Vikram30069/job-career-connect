# 💼 Career Connect (MERN Stack)

A comprehensive **Job Portal Application** built using the **MERN stack**. **Career Connect** empowers users to seamlessly browse job listings, apply for positions, and manage applications—all in one platform.

---

## 🚀 Features

- **🔒 User Authentication:** Secure login and registration with JWT for both job seekers and employers.
- **📝 Job Listings:** Explore a wide range of job opportunities stored in MongoDB.
- **📋 Application Management:** 
  - **Job Seekers:** Track and manage your applications effortlessly.
  - **Employers:** View and organize received applications.
- **📱 Responsive Design:** Enjoy a smooth, intuitive experience on any device.

---

## 🛠️ Technologies Used

- **Frontend:**
  - [React.js](https://reactjs.org/) 
  - [React Router](https://reactrouter.com/)
  - [Bootstrap](https://getbootstrap.com/)
- **Backend:**
  - [Node.js](https://nodejs.org/)
  - [Express.js](https://expressjs.com/)
  - [MongoDB](https://www.mongodb.com/)
- **Authentication:** 
  - JWT (JSON Web Tokens)
  - Bcrypt for password hashing
- **Image Upload:** 
  - [Cloudinary](https://cloudinary.com/)
- **Deployment:** 
  - [Vercel](https://vercel.com/) (Frontend)
  - [Render](https://render.com/) (Backend)
  - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (Database)

---

## 🔧 Getting Started

Follow these steps to set up **Career Connect** locally:

### ⚙️ Prerequisites

- **Node.js:** Latest version (v22.2.0 or above).
- **MongoDB:** MongoDB Atlas account or a local MongoDB server.
- **Cloudinary:** Account for image storage and management.

### 📥 Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/exclusiveabhi/career_connect.git
   ```

2. **Install Dependencies:**
   ```sh
   cd career_connect/backend
   npm install

   cd ../frontend
   npm install
   ```

3. **Set Up Environment Variables:**
   - Create a `config.env` file inside a `config` folder in the **backend** directory.
   - Add the following variables:
     ```env
     PORT=
     CLOUDINARY_API_KEY=
     CLOUDINARY_API_SECRET=
     CLOUDINARY_CLOUD_NAME=
     FRONTEND_URL=
     DB_URL=
     JWT_SECRET_KEY=
     JWT_EXPIRE=
     COOKIE_EXPIRE=
     ```
   - Replace each placeholder with your configuration details.

4. **Run the Application:**
   ```sh
   npm run dev
   ```

5. **Access the App:**
   Open your browser and navigate to [http://localhost:5173](http://localhost:5173)

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. **Fork the Project**
2. **Create Your Feature Branch:**
   ```sh
   git checkout -b feature/AmazingFeature
   ```
3. **Commit Your Changes:**
   ```sh
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch:**
   ```sh
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request:**
   - We strive to merge within 24 hours.

If you find **Career Connect** useful, please give it a ⭐.

---

## 📬 Contact

**Abhishek Rajput**  
[GitHub Profile](https://github.com/Vikram30069)

Project Link: [https://github.com/exclusiveabhi/career_connect.git](https://github.com/Vikram30069/career_connect.git)
