# CodeSync

A collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.

##  Features

-  Real-time collaboration on code editing across multiple files
-  Create, open, edit, save, delete, and organize files and folders
-  Option to download the entire codebase as a zip file
-  Unique room generation with room ID for collaboration
-  Comprehensive language support for versatile programming
-  Syntax highlighting for various file types with auto-language detection
-  Code Execution: Users can execute the code directly within the collaboration environment
-  Instant updates and synchronization of code changes across all files and folders
-  Notifications for user join and leave events
-  User presence list with online/offline status indicators
-  Real-time group chatting functionality
-  Multiple themes for personalized coding experience
-  Collaborative Drawing in real-time
-  AI-powered Copilot for code generation

##  Tech Stack

- **Frontend:** React, TypeScript, Tailwind CSS, Vite
- **Backend:** Node.js, Express.js, Socket.io

##  Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Setup

1. **Clone the repository:**
   ``ash
   git clone https://github.com/<your-username>/CodeSync.git
   cd CodeSync
   ``

2. **Create .env files:**

   **Client (.env):**
   ``ash
   VITE_BACKEND_URL=http://localhost:3000
   ``

   **Server (.env):**
   ``ash
   PORT=3000
   PISTON_API_URL=https://emkc.org/api/v2/piston
   POLLINATIONS_API_URL=https://text.pollinations.ai
   ``

3. **Install dependencies:**
   ``ash
   # Frontend
   cd client
   npm install
   
   # Backend
   cd ../server
   npm install
   ``

4. **Start the servers:**
   ``ash
   # Terminal 1 - Backend
   cd server
   npm run dev
   
   # Terminal 2 - Frontend
   cd client
   npm run dev
   ``

5. **Access the application:**
   ```
   http://localhost:5173/
   ```

##  Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.
