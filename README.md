# GigConnect - A Gig-based Platform for Connecting Workers and Users

GigConnect is a platform designed to connect skilled workers with users in need of services. Whether it's finding a plumber, carpenter, or other skilled professionals, GigConnect provides an easy-to-use interface for both workers and users to interact, submit requests, and find the right talent quickly.

## Features

### 1. **User & Worker Registration**
   - Users and workers can create accounts on the platform.
   - Workers can register with detailed profiles including their profession, skills, hourly rate, and contact information.
   - Secure authentication using Firebase Auth.

### 2. **Worker Dashboard**
   - Workers have a personalized dashboard to manage their profiles and job requests.
   - Ability to update skills, hourly rate, and other personal details.
   - Receive connection requests from users based on location and profession.

### 3. **Search & Filter Functionality**
   - Users can search for workers by profession (plumber, carpenter, etc.).
   - Filter workers by skills, hourly rate, and availability.
   - Integrated with MongoDB Atlas Vector Search to ensure fast and accurate results.

### 4. **Location-Based Worker Search**
   - Integrated map to search for workers based on user location.
   - Display workers available in the selected area.
   - Uses free APIs for mapping and location-based search.

### 5. **Voice Assistant Integration**
   - Voice search functionality using MongoDB Atlas Vector Search and FAISS.
   - Understand and respond to user queries in Hindi, such as **"Mujhe plumber chahiye apna Una ke area mai."**
   - Implemented with **Whisper.cpp** for Speech-to-Text (STT) and **Coqui TTS** for Text-to-Speech (TTS).
   - Integrated with **Alan AI** for voice assistant management.

### 6. **Cloud Deployment**
   - The project is deployed on Vercel for the frontend and MongoDB Atlas for the backend.
   - Uses Cloudflare for CDN and security enhancements.
7. **Gemini AI Integration**
   - Gemini AI is integrated into the platform as a **FAQ chatbot** for users and workers to get quick responses.
   - The chatbot leverages **Gemini's API** to answer a wide range of questions related to the platform and services, providing real-time assistance.
   - This integration helps streamline user interactions and improve user experience by
### 8. **Mobile-Friendly Interface**
   - Fully responsive design to ensure the platform is accessible on both desktop and mobile devices.

### 9. **Worker Data API**
   - Workers’ profiles and data are managed through a RESTful API.
   - Supports dynamic fetching of worker data based on user queries.

---

## Tech Stack
- **Frontend:** React, TypeScript
- **Backend:** Node.js, Express
- **Database:** MongoDB Atlas, FAISS for Vector Search
- **Authentication:** Firebase Auth
- **Voice Assistant:** Alan AI, Whisper.cpp, Coqui TTS
- **Deployment:** Vercel, MongoDB Atlas, Cloudflare

## Setup

### Prerequisites
1. Node.js (v14+)
2. Gemini Api
3. MongoDB Atlas account for database hosting

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/gigconnect.git
