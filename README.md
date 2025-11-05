# 💼 Job Portal - Full Stack Web Application

A complete job portal web application built with **MERN Stack** (MongoDB, Express, React, Node.js)

![Job Portal](https://img.shields.io/badge/MERN-Stack-green)
![React](https://img.shields.io/badge/React-18-blue)
![Node](https://img.shields.io/badge/Node.js-Express-yellow)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-brightgreen)

---

## 🌟 Features

### For Job Seekers:
- ✅ User Registration & Login
- ✅ Browse Jobs with Advanced Search & Filters
- ✅ View Detailed Job Descriptions
- ✅ Apply for Jobs with Cover Letter
- ✅ Track Application Status
- ✅ Personal Dashboard
- ✅ Withdraw Applications

### For Employers:
- ✅ Post New Job Listings
- ✅ Manage Posted Jobs
- ✅ View All Applications
- ✅ Shortlist/Reject Candidates
- ✅ View Applicant Details
- ✅ Analytics Dashboard
- ✅ Delete Job Postings

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Bootstrap 5
- React Router
- Axios
- React Icons

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt

## 🚀 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (running locally or MongoDB Atlas)
- Git

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/RITHIK.git
cd RITHIK
```

### 2. Backend Setup
```bash
# Install dependencies
npm install

# Create .env file with these variables:
PORT=3000
MONGODB_URI=mongodb://localhost:27017/jobportal
JWT_SECRET=your_secret_key_here

# Start backend server
node server.js
```

### 3. Frontend Setup
```bash
# Navigate to client folder
cd client

# Install dependencies
npm install

# Start React development server
npm start
```

### 4. Access the Application
Open your browser and go to:
```
http://localhost:3001
```

---

## 📁 Project Structure
```
RITHIK/
├── models/
│   ├── User.js           # User schema
│   ├── Job.js            # Job schema
│   └── Application.js    # Application schema
├── routes/
│   ├── auth.js           # Authentication routes
│   ├── jobs.js           # Job routes
│   └── applications.js   # Application routes
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/   # Reusable components
│   │   ├── pages/        # Page components
│   │   ├── context/      # React context
│   │   ├── utils/        # API utilities
│   │   └── styles/       # CSS files
│   └── package.json
├── server.js             # Main server file
├── .env                  # Environment variables
├── .gitignore
├── package.json
└── README.md
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:
```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/jobportal
JWT_SECRET=your_super_secret_key_change_in_production
```

---

## 🎯 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user
- `GET /api/auth/me` - Get current user

### Jobs
- `GET /api/jobs` - Get all jobs (with filters)
- `GET /api/jobs/:id` - Get single job
- `POST /api/jobs` - Create job (Employer only)
- `PUT /api/jobs/:id` - Update job (Employer only)
- `DELETE /api/jobs/:id` - Delete job (Employer only)
- `GET /api/jobs/my/posted` - Get employer's jobs

### Applications
- `POST /api/applications` - Apply for job (Job Seeker only)
- `GET /api/applications/my` - Get user's applications
- `GET /api/applications/job/:jobId` - Get job applications (Employer only)
- `PUT /api/applications/:id/status` - Update application status
- `DELETE /api/applications/:id` - Delete application

---

## 👥 User Roles

### Job Seeker
- Can browse and search jobs
- Can apply for jobs
- Can view and manage their applications
- Can withdraw applications

### Employer
- Can post new jobs
- Can manage their job listings
- Can view applications for their jobs
- Can shortlist/reject candidates

---

## 🎨 Features Highlights

- **Responsive Design** - Works on all devices
- **Real-time Updates** - Dynamic data rendering
- **Secure Authentication** - JWT token-based auth
- **Password Encryption** - Bcrypt hashing
- **Role-based Access** - Different features for different users
- **Advanced Search** - Filter by location, type, category, experience
- **Beautiful UI** - Modern gradient design with Bootstrap

---

## 🧪 Testing

### Demo Accounts

**Employer Account:**
```
Email: employer@demo.com
Password: 123456
```

**Job Seeker Account:**
```
Email: seeker@demo.com
Password: 123456
```

---

## 📝 Usage

1. **Register** as either Employer or Job Seeker
2. **Employers** can post jobs and manage applications
3. **Job Seekers** can browse, search, and apply for jobs
4. Both can view their respective dashboards
5. Track application status in real-time

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📄 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Developer

**DHAGAI RITHIK**
- GitHub:(https://github.com/RITHIK-1434)
- Email:dhagaisandhya0@gmail.com

---

## 🙏 Acknowledgments

- React.js Documentation
- MongoDB Documentation
- Bootstrap Documentation
- Express.js Documentation

---

---

**Made with ❤️ by RITHIK **
