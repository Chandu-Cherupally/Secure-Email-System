Secure Email System

A cryptography-based secure email application that ensures Confidentiality, Integrity, and Authentication (CIA) for email communication using modern encryption techniques. The system supports secure one-to-one and group email communication with encrypted attachments.

📌 Project Overview

The Secure Email System is designed to protect email communication against common security threats such as eavesdropping, message tampering, and impersonation. It integrates RSA, AES, and SHA-512 cryptographic algorithms to provide end-to-end security while maintaining usability.

The project also supports secure group messaging, where a single email can be sent to multiple recipients while preserving individual confidentiality by generating and encrypting unique AES keys for each recipient.

🔐 Security Features

Confidentiality
Email content and attachments encrypted using AES
AES keys encrypted using recipient-specific RSA public keys

Integrity
SHA-512 hashing ensures detection of any message tampering

Authentication
RSA-based digital signatures verify sender authenticity

Secure Group Messaging
Unique AES key generated per recipient
Same security guarantees as one-to-one communication

🧠 Cryptographic Algorithms Used
Algorithm	Purpose
RSA	Key exchange, digital signatures
AES	Email and attachment encryption
SHA-512	Message integrity verification

🚀 Getting Started
Prerequisites
Node.js (v16 or above)
npm or yarn

Installation
cd client
npm install

Run the Application
npm run dev

The application will be available at:
http://localhost:5173

🧪 Testing & Validation
Tested for secure email transmission
Verified integrity checks using SHA-512
Validated encryption/decryption for both individual and group messaging
Attachments tested with encrypted storage and retrieval

🧩 Design Principles Followed
Modular architecture
Separation of concerns
Secure-by-design approach
Scalable cryptographic workflow
Clean and maintainable codebase

📄 Documentation
Detailed design explanations, algorithms, and diagrams are available in DOCS folder

🛡️ Security Note
This project is developed for academic and learning purposes.
While strong cryptographic standards are used, it should be audited before any production deployment.

👨‍💻 Authors
Chandu Cherupally (22CSB0C20)
Manoj Kumar Samudrala (22CSB0C23)
