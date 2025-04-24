# YouTube Clone: Full-Stack Video Streaming Platform

## Project Overview

This project is a full-stack web application that emulates core functionalities of YouTube, allowing users to browse, search, and view videos. Built with modern web technologies, the application provides a seamless user experience with features such as video playback, search functionality, and responsive design.

## Key Technical Highlights

- **Frontend Development**: Utilized React.js for building dynamic user interfaces, with Tailwind CSS for styling and responsiveness.
- **Routing**: Implemented client-side routing using React Router to manage navigation between different views.
- **API Integration**: Integrated with the YouTube Data API to fetch real-time video data, including video details, search results, and trending videos.
- **State Management**: Managed application state effectively using React's Context API.

## Detailed Steps

### 1. Project Setup

- **Cloning the Repository**:
  ```bash
  git clone https://github.com/YashRangucha/youtube-clone-main.git
  cd youtube-clone-main
## Install Dependencies & API Configuration:
- npm install

- Get a YouTube Data API key from the Google Developers Console.
Create a .env file in the project root: 
REACT_APP_YOUTUBE_API_KEY=your_api_key_here

## Start the Application:
- npm start
- Open http://localhost:3000 in your browser.
  
## Feature Implementation
- Home Page: Displays trending videos fetched using YouTube Data API.
- Search Bar: Dynamically queries videos based on user input.
- Video Detail Page: Embedded video, metadata, and related suggestions.
- Sidebar Navigation: Categorical quick links (music, gaming, news, etc.)
- Responsive UI: Works across desktop, tablet, and mobile screens.

## 📊 Key Insights
- API-based frontend development allows real-time, dynamic rendering.
- Modular React structure ensures scalability and reusability.
- Tailwind CSS accelerates development while delivering responsive UIs.
- Context API effectively replaces heavier global state managers for small/medium apps.

## 💡 Future Enhancements
- 🔐 Authentication: Add Firebase Auth or OAuth login
- 🎥 Video Uploading Simulation
- 💬 Comments Section under each video
- ❤️ Like, Subscribe, Share options
- 🧠 Watch History & Video Recommendations
- 🌙 Dark Mode Toggle

## 🧰 Technologies Used
- Frontend: React.js, Tailwind CSS, React Router
- API: YouTube Data API v3
- State Management: Context API
- Version Control: Git & GitHub

