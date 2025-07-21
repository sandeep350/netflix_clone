# 🎬 Netflix Clone

A responsive and dynamic clone of Netflix built for educational purposes. This project replicates core Netflix features like browsing movies, authentication, and video streaming UI.

## 🚀 Features

- User Authentication (Sign In / Sign Up)
- Browse trending movies and TV shows
- Movie details and trailers
- Responsive UI (Mobile / Desktop)
- Search functionality
- Add to "My List" feature (optional)
- Dark-themed Netflix-style UI

## 🛠️ Tech Stack

Frontend:
- React.js
- Axios (for API calls)
- Firebase (for Auth & Hosting)
- React Router DOM
- TMDB API (for movie data)
- Tailwind CSS / CSS Modules / Styled Components

Backend (optional):
- Node.js + Express
- MongoDB / Firebase Realtime Database

📦 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/netflix-clone.git
cd netflix-clone
Install dependencies:

bash
Copy
Edit
npm install
Configure environment variables:

Create a .env file in the project root.

Add your TMDB API key and Firebase configuration:

bash
Copy
Edit
REACT_APP_TMDB_API_KEY=your_tmdb_api_key
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_firebase_app_id
Start the development server:

bash
Copy
Edit
npm start
Access the app:

Open your browser and go to http://localhost:3000

📤 Deployment
To deploy the project using Firebase Hosting:

bash
Copy
Edit
npm run build
firebase login
firebase init
firebase deploy
🙌 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for improvements.

⚠️ Disclaimer
This project is created for educational purposes only and is not intended for commercial use. All media content belongs to their respective owners.


