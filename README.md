# Tripz

Tripz is a web app that generates travel plans based on categories using TypeScript, React Router, and Google Gemini AI. It fetches destination images from Unsplash and uses Appwrite for backend and Google sign-in authentication. The app is fully responsive with account management, a travel statistics dashboard, and enhanced UI using Syncfusion components.

## Features

- ⚡️ Travel plan generation with Google Gemini AI
- 🌅 Destination images from Unsplash
- 🔥 Hot Module Replacement (HMR)
- 🔄 Routing with React Router
- 🚀 Server-side rendering
- 🔒 Google authentication
- 📈 Travel statistics dashboard
- 🖥️ Responsive design
- 🛠️ Backend with Appwrite
- 👤 Account management
- 🎨 TailwindCSS styling
- 🧩 Syncfusion UI components

## Tech Stack

- TypeScript
- React
- React Router
- Tailwind CSS
- Appwrite
- Syncfusion
- Google Gemini
- Unsplash


## Cloning the Repository

```sh
git clone https://github.com/wwafii/travel-agency-dashboard.git
cd travel-agency-dashboard
```

## Installation

Install the project dependencies using npm:

```sh
npm install
```


## Set Up Environment Variables

Create a new file named `.env.local` in the root of your project and add the following content:
```sh
VITE_SYNCFUSION_LICENSE_KEY=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_API_KEY=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_USERS_COLLECTION_ID=
VITE_APPWRITE_TRIPS_COLLECTION_ID=
VITE_APPWRITE_API_ENDPOINT=
GEMINI_API_KEY=
UNSPLASH_ACCESS_KEY=
```

Replace the values with your actual AppWrite credentials.


## Running the Project

Start the development server:
```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.