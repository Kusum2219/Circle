# SafeCircle

SafeCircle is an AI-powered safety and assistance web application designed to help users analyze potentially unsafe situations and access intelligent safety support. It combines modern web technologies, Firebase services, AI capabilities, OCR, and risk assessment to create a user-focused digital safety platform.

Features

- AI-Powered Safety Analysis
  Uses Google Gemini Flash to provide intelligent analysis and assistance for safety-related situations.

- Risk Scoring
  Evaluates available information and generates a risk assessment to help users understand the potential level of danger.

- OCR-Based Information Extraction
  Extracts relevant information from uploaded images or documents using Optical Character Recognition (OCR).

- User Authentication
  Secure user authentication is implemented using Firebase Authentication.

- Cloud Data Storage
  Firebase Firestore is used for storing and managing application data.

- Responsive Interface
  Built with React and Tailwind CSS for a modern and responsive user experience.

- AI-Assisted Support
  Integrates generative AI to provide contextual responses and safety-related guidance.

Tech Stack

Frontend

- React.js
- Tailwind CSS
- JavaScript

Backend & Cloud

- Firebase Authentication
- Firebase Firestore

Artificial Intelligence

- Google Gemini Flash
- AI-based risk assessment
- OCR-based text extraction

Development Tools

- Google AI Studio
- Firebase

Application Workflow

User
  |
  v
React Frontend
  |
  +----------------------+
  |                      |
  v                      v
Firebase Auth        User Input / Image
                         |
                         v
                       OCR
                         |
                         v
                  Extracted Information
                         |
                         v
                  Gemini Flash AI
                         |
                         v
                   Risk Analysis
                         |
                         v
                  Safety Response
                         |
                         v
                      User

Project Architecture

SafeCircle
│
├── Frontend
│   ├── React.js
│   ├── Tailwind CSS
│   └── User Interface
│
├── Authentication
│   └── Firebase Authentication
│
├── Database
│   └── Firebase Firestore
│
├── AI Layer
│   ├── Google Gemini Flash
│   ├── Risk Assessment
│   └── AI Safety Analysis
│
└── OCR
    └── Image / Document Information Extraction

How It Works

1. The user accesses the SafeCircle web application.
2. The user authenticates using Firebase Authentication.
3. The user provides safety-related information or uploads an image/document.
4. OCR extracts useful information from supported images/documents.
5. The extracted or user-provided information is processed using Google Gemini Flash.
6. The AI analyzes the information and generates a contextual response.
7. A risk assessment is generated based on the available information.
8. The result is presented to the user through the React interface.
9. Relevant application data is stored and managed using Firebase Firestore.

Key Highlights

- AI-powered safety assistance
- Gemini Flash integration
- OCR-based information extraction
- Automated risk assessment
- Firebase authentication
- Cloud-based Firestore database
- React-based responsive frontend
- Tailwind CSS UI
- User-centric safety approach

Purpose

SafeCircle aims to combine Artificial Intelligence, OCR, and modern web technologies to create a digital safety platform that can assist users in identifying and understanding potentially risky situations.

Future Enhancements

- Real-time emergency alerts
- Trusted-contact notifications
- Location-based safety features
- Improved AI risk detection
- Emergency service integration
- Advanced analytics and safety history
- Mobile application support

Technologies Used

Technology| Purpose
React.js| Frontend development
Tailwind CSS| UI styling
Firebase Authentication| User authentication
Firebase Firestore| Data storage
Google Gemini Flash| AI analysis
OCR| Information extraction
Google AI Studio| AI development and integration
