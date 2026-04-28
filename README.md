#Features
Detect deepfake from images and videos (real/fake classification with score)
Combine results from multiple AI models (fusion approach) to improve accuracy
Upload media directly from the UI and receive results in real time
User authentication system:
Email/password login (JWT-based)
OTP verification for new devices
Google OAuth2 login
Face ID:
Face registration and login
Anti-spoofing (liveness detection)
Security features:
Rate limiting
Input validation
Optional reCAPTCHA
Logging and health check APIs

#Technologies Used
Frontend: React, Vite, Tailwind CSS
Backend: Node.js, Express, PostgreSQL
Authentication: JWT, bcrypt, Google OAuth2
AI Integration: FastAPI (deepfake models), AI Gateway (Express proxy)
Security: Helmet, CORS, express-rate-limit, reCAPTCHA
Other: Multer (file upload), Nodemailer (OTP email)
