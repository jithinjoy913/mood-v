# Mood Verse

A modern web application that analyzes your mood using face-api.js for face detection and provides personalized recommendations for music, movies, and activities.

## Features

- Real-time face detection using face-api.js
- Mood analysis and personalized recommendations
- Firebase authentication
- Interactive mood quiz
- Responsive design with Tailwind CSS

## Tech Stack

- React
- TypeScript
- face-api.js
- Firebase Authentication
- Tailwind CSS
- Zustand for state management

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/jithinjoy913/mood-v.git
```

2. Install dependencies:
```bash
cd mood-v
npm install
```

3. Set up Firebase:
   - Create a new Firebase project
   - Enable Email/Password authentication
   - Copy your Firebase config
   - Update `src/lib/firebase.ts` with your config

4. Start the development server:
```bash
npm run dev
```

