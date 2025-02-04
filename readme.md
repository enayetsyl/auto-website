# Auto Website Deployment Tool

## Overview
The **Auto Website Deployment Tool** is a web application that allows users to customize and deploy websites quickly. Users can input details such as colors, images, headings, and text, and the tool will automatically clone a base repository, modify the content, install dependencies, and deploy the website to Vercel.

## Features
- Clone a predefined repository as a base template.
- Customize project details such as colors, images, text, and layout.
- Automatically install dependencies and deploy the project to Vercel.
- User-friendly React-based UI for easy customization.

## Tech Stack
### Backend
- **Node.js** with **Express.js**
- **CORS** for handling cross-origin requests
- **Body-parser** for JSON parsing
- **fs (File System)** for modifying configuration files
- **child_process (exec)** for executing shell commands

### Frontend
- **React.js** with Vite
- **React Router** for navigation
- **Axios** for API communication
- **TailwindCSS** for styling

## Installation
### Prerequisites
Make sure you have the following installed on your system:
- **Node.js** (v18 or later)
- **npm** or **yarn**
- **Vercel CLI** (for deployment)

### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/enayetsyl/auto-website.git
   cd auto-website-deployment
   ```
2. Install backend dependencies:
   ```sh
   npm install
   ```
3. Start the backend server:
   ```sh
   npm start
   ```
   The server will run on **http://localhost:3001**.

### Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```
2. Install frontend dependencies:
   ```sh
   npm install
   ```
3. Start the frontend development server:
   ```sh
   npm run dev
   ```
   The frontend will run on **http://localhost:5173**.

## API Endpoints
### **1. Clone and Deploy Project**
- **Endpoint:** `POST /clone-and-install`
- **Headers:**
  - `Content-Type: application/json`
- **Request Body:**
  - Project details including colors, images, text, and customization options.
- **Response:** Returns the deployment URL on successful deployment.

## Folder Structure
```
/auto-website-deployment
├── backend/
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── LinkToPdf.jsx
│   │   │   ├── VideoToPdf.jsx
│   │   │   ├── PdfMerge.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   ├── package.json
│   ├── tailwind.config.js
│   ├── vite.config.js
│   ├── index.html
│   ├── public/
├── README.md
```

## Dependencies
### Backend
```json
"dependencies": {
  "cors": "^2.8.5",
  "express": "^4.19.2",
  "body-parser": "^1.20.2",
  "fs": "^0.0.1-security",
  "path": "^0.12.7"
}
```

### Frontend
```json
"dependencies": {
  "axios": "^1.7.1",
  "react": "^18.3.1",
  "react-dom": "^18.3.1",
  "react-router-dom": "^6.29.0",
  "tailwindcss": "^4.0.3"
}
```

## Future Enhancements
- Support for more deployment platforms (e.g., Netlify, AWS Amplify).
- Improved error handling and detailed logs.
- User authentication and project history tracking.

## License
This project is licensed under the **ISC License**.

## Author
- **Your Name** (Replace with actual author)

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 🏆 **Author:** Md Enayetur Rahman

### Contact Information
- [LinkedIn](https://www.linkedin.com/in/md-enayetur-rahman/)
- [Facebook](https://www.facebook.com/profile.php?id=100094416483981)
- [X (Twitter)](https://x.com/enayetu_syl)
- [YouTube](https://www.youtube.com/@MdEnayeturRahman)
- [GitHub](https://github.com/enayetsyl/)
- [Medium](https://medium.com/@enayetflweb)
- [dev.to](https://dev.to/md_enayeturrahman_2560e3)
- [Leetcode](https://leetcode.com/u/XTl7hvNPIc/)
- [Hackerrank](https://www.hackerrank.com/profile/enayetflweb)
- [Codeforces](https://codeforces.com/profile/enayetsyl)
- [Email](mailto:enayetflweb@gmail.com)