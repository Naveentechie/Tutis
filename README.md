
I developed a secure employee authentication system that implements multi-factor authentication (MFA) using a three-layered hashing algorithm and biometric authenticators. The system enhances security by generating hashed passwords and verifying the user's identity through facial recognition technology. This combination of advanced cryptographic techniques and biometric authentication ensures robust access control and data protection for organizations.

🔧 Backend Setup
🗄️ Database Setup
🔐 Signup Endpoint
📧 Sending Verify Account Email
🔍 Verify Email Endpoint
📄 Building a Welcome Email Template
🚪 Logout Endpoint
🔑 Login Endpoint
🔄 Forgot Password Endpoint
🔁 Reset Password Endpoint
✔️ Check Auth Endpoint
🌐 Frontend Setup
📋 Signup Page UI
🔓 Login Page UI
✅ Email Verification Page UI
📤 Implementing Signup
📧 Implementing Email Verification
🔒 Protecting Our Routes
🔑 Implementing Login
🏠 Dashboard Page
🔄 Implementing Forgot Password
🚀 Super Detailed Deployment
✅ This is a lot of work. Support my work by subscribing to the Channel
Setup .env file
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token
MAILTRAP_ENDPOINT=https://send.api.mailtrap.io/

CLIENT_URL= http://localhost:5173
Run this app locally
npm run build
Start the app
npm run start