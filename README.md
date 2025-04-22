# E-Commerce Demo

A modern e-commerce web application built with React, Chakra UI, and Firebase.

## Tech Stack

- **Frontend**: React 19, TypeScript
- **UI Library**: Chakra UI
- **State Management**: React Context API
- **Authentication & Database**: Firebase
- **Routing**: React Router v7
- **Animations**: Framer Motion

## Features

- Responsive design for all device sizes
- Product categorization and filtering
- User authentication (sign up, login, profile management)
- Shopping cart functionality
- Checkout process
- Order history
- Admin dashboard for product management

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Firebase account

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/themanojraghav/ecomm-demo.git
   cd ecomm-demo
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the root directory with your Firebase configuration:
   ```
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```

4. Start the development server:
   ```
   npm start
   ```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App

## Deployment

This application can be deployed to Firebase Hosting:

1. Install Firebase CLI:
   ```
   npm install -g firebase-tools
   ```

2. Login to Firebase:
   ```
   firebase login
   ```

3. Initialize Firebase:
   ```
   firebase init
   ```

4. Deploy to Firebase:
   ```
   firebase deploy
   ```

## License

MIT
