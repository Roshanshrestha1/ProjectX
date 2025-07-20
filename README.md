# ☁️ ProjectX - Cloud File Sharing Platform

> **Secure Cloud File Sharing Web App with AWS S3, React, Node.js, and MongoDB**

![ProjectX Logo](https://img.shields.io/badge/ProjectX-Cloud%20Storage-blue)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![Node.js](https://img.shields.io/badge/Node.js-16.0+-green)
![AWS S3](https://img.shields.io/badge/AWS-S3-orange)
![MongoDB](https://img.shields.io/badge/MongoDB-6.4+-green)

## 🚀 **Project Overview**

ProjectX is a comprehensive cloud file sharing platform that provides secure, scalable, and user-friendly file storage and sharing capabilities. Built with modern technologies, it offers enterprise-grade security features while maintaining an intuitive user experience.

## ✨ **Key Features**

### 🔐 **Security & Authentication**
- **JWT-based Authentication** with secure token management
- **Role-based Access Control** (Admin, User, Guest)
- **File Encryption** for sensitive data
- **Rate Limiting** to prevent abuse
- **CORS Protection** and security headers

### 📁 **File Management**
- **Drag & Drop Upload** with progress tracking
- **Multiple File Types** support (Images, Documents, Videos, etc.)
- **File Preview** for common formats
- **Bulk Operations** (Upload, Download, Delete)
- **File Versioning** and history tracking

### 🌐 **Cloud Storage**
- **AWS S3 Integration** for scalable storage
- **CDN Support** for fast global access
- **Automatic Backup** and redundancy
- **Storage Analytics** and usage tracking

### 👥 **Collaboration**
- **File Sharing** with custom permissions
- **Public/Private Links** generation
- **Team Workspaces** for group collaboration
- **Real-time Notifications** for file activities

### 📊 **Analytics & Monitoring**
- **Usage Statistics** and storage metrics
- **Activity Logs** and audit trails
- **Performance Monitoring** and optimization
- **User Analytics** and behavior tracking

## 🛠️ **Technology Stack**

### **Frontend**
- **React 18** - Modern UI framework
- **React Router** - Client-side routing
- **Tailwind CSS** - Utility-first styling
- **React Dropzone** - File upload handling
- **React Hot Toast** - User notifications
- **React Icons** - Icon library

### **Backend**
- **Node.js** - Server runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - ODM for MongoDB
- **Multer** - File upload middleware

### **Cloud Services**
- **AWS S3** - Object storage
- **AWS CloudFront** - Content delivery
- **AWS IAM** - Identity and access management

### **Security & Performance**
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing
- **Helmet** - Security headers
- **Rate Limiting** - API protection
- **Compression** - Response optimization

## 📁 **Project Structure**

```
ProjectX/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── Auth/
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   └── ForgotPassword.js
│   │   ├── Dashboard/
│   │   │   ├── Dashboard.js
│   │   │   ├── FileManager.js
│   │   │   └── Analytics.js
│   │   ├── FileUpload/
│   │   │   ├── Dropzone.js
│   │   │   ├── ProgressBar.js
│   │   │   └── FilePreview.js
│   │   ├── Navigation/
│   │   │   ├── Navbar.js
│   │   │   ├── Sidebar.js
│   │   │   └── Breadcrumb.js
│   │   └── UI/
│   │       ├── Button.js
│   │       ├── Modal.js
│   │       └── Loading.js
│   ├── services/
│   │   ├── api.js
│   │   ├── auth.js
│   │   └── storage.js
│   ├── utils/
│   │   ├── constants.js
│   │   ├── helpers.js
│   │   └── validators.js
│   ├── hooks/
│   │   ├── useAuth.js
│   │   ├── useFiles.js
│   │   └── useUpload.js
│   ├── context/
│   │   ├── AuthContext.js
│   │   └── FileContext.js
│   ├── styles/
│   │   └── index.css
│   ├── App.js
│   └── index.js
├── server/
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── fileController.js
│   │   └── userController.js
│   ├── middleware/
│   │   ├── auth.js
│   │   ├── upload.js
│   │   └── validation.js
│   ├── models/
│   │   ├── User.js
│   │   ├── File.js
│   │   └── Share.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── files.js
│   │   └── users.js
│   ├── config/
│   │   ├── database.js
│   │   ├── aws.js
│   │   └── email.js
│   ├── utils/
│   │   ├── logger.js
│   │   └── helpers.js
│   └── index.js
├── package.json
├── tailwind.config.js
└── README.md
```

## 🚀 **Getting Started**

### **Prerequisites**
- Node.js (v14 or higher)
- npm or yarn
- MongoDB database
- AWS S3 bucket
- AWS credentials

### **Installation**

1. **Clone the repository**
   ```bash
   git clone https://github.com/Roshanshrestha1/ProjectX.git
   cd ProjectX
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create `.env` files in both root and server directories:

   **Root `.env`:**
   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   REACT_APP_S3_BUCKET=your-s3-bucket-name
   REACT_APP_AWS_REGION=us-east-1
   ```

   **Server `.env`:**
   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/projectx
   JWT_SECRET=your-jwt-secret-key
   AWS_ACCESS_KEY_ID=your-aws-access-key
   AWS_SECRET_ACCESS_KEY=your-aws-secret-key
   AWS_REGION=us-east-1
   S3_BUCKET=your-s3-bucket-name
   EMAIL_SERVICE=gmail
   EMAIL_USER=your-email@gmail.com
   EMAIL_PASS=your-email-password
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Access the application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## 🔧 **Configuration**

### **AWS S3 Setup**
1. Create an S3 bucket
2. Configure CORS policy
3. Set up IAM user with S3 permissions
4. Configure bucket policies

### **MongoDB Setup**
1. Install MongoDB locally or use MongoDB Atlas
2. Create database and collections
3. Set up indexes for performance

### **Email Configuration**
1. Configure SMTP settings
2. Set up email templates
3. Test email functionality

## 📱 **Usage Guide**

### **User Registration & Authentication**
1. Navigate to the registration page
2. Fill in required information
3. Verify email address
4. Login with credentials

### **File Upload**
1. Drag and drop files or click to browse
2. Monitor upload progress
3. Add file descriptions and tags
4. Set sharing permissions

### **File Management**
1. View files in dashboard
2. Organize with folders
3. Share files with others
4. Download or delete files

### **Collaboration**
1. Create shared workspaces
2. Invite team members
3. Set access permissions
4. Monitor activity logs

## 🔒 **Security Features**

### **Authentication & Authorization**
- JWT token-based authentication
- Password hashing with bcrypt
- Role-based access control
- Session management

### **File Security**
- File encryption at rest
- Secure file transfer (HTTPS)
- Access control lists
- Audit logging

### **API Security**
- Rate limiting
- Input validation
- SQL injection prevention
- XSS protection

## 📊 **Performance Optimization**

### **Frontend**
- Code splitting and lazy loading
- Image optimization
- Caching strategies
- Bundle size optimization

### **Backend**
- Database indexing
- Query optimization
- Caching with Redis
- CDN integration

### **Storage**
- S3 lifecycle policies
- Compression algorithms
- CDN distribution
- Backup strategies

## 🧪 **Testing**

### **Frontend Testing**
```bash
npm test
```

### **Backend Testing**
```bash
npm run test:server
```

### **E2E Testing**
```bash
npm run test:e2e
```

## 📈 **Deployment**

### **Heroku Deployment**
1. Create Heroku app
2. Configure environment variables
3. Deploy using Git
4. Set up custom domain

### **AWS Deployment**
1. Deploy to EC2 or ECS
2. Configure load balancer
3. Set up auto-scaling
4. Monitor with CloudWatch

### **Docker Deployment**
```bash
# Build Docker image
docker build -t projectx .

# Run container
docker run -p 3000:3000 -p 5000:5000 projectx
```

## 🤝 **Contributing**

1. Fork the repository
2. Create feature branch
3. Make changes
4. Add tests
5. Submit pull request

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 **Author**

**Roshan Shrestha**
- Email: roshanshrestha9821533789@gmail.com
- GitHub: [@Roshanshrestha1](https://github.com/Roshanshrestha1)
- Portfolio: [Portfolio Website](https://roshanshrestha1.github.io/Roshanshrestha1/)

## 🙏 **Acknowledgments**

- AWS for cloud infrastructure
- MongoDB for database solution
- React team for the amazing framework
- All contributors and supporters

---

**Made with ❤️ by Roshan Shrestha**

*Full-Stack Developer & Cybersecurity Expert* 
