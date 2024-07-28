# Netflix Clone

A fully functioning web clone of Netflix built with React and Vite.

## Features

- **Login and Signup:** User authentication and management using Firebase.
- **Frontend:** Built using React for a smooth and dynamic user experience.
- **Deployment:** The project is deployed and can be accessed at [Netflix-MERN](https://moviesbyshruti.netlify.app/).

## Getting Started

### Prerequisites

Ensure you have Node.js and npm installed on your machine. You can download Node.js from [here](https://nodejs.org/).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shrutigupta02/Netflix.git
   cd Netflix/netflix-frontend
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Set up Firebase for user authentication and management. Follow the Firebase setup instructions to get your configuration details.

4. Create a `.env` file in the root directory of your project and add your Firebase configuration:

   ```env
   FIREBASE_API_KEY=your_api_key
   FIREBASE_AUTH_DOMAIN=your_auth_domain
   FIREBASE_PROJECT_ID=your_project_id
   FIREBASE_STORAGE_BUCKET=your_storage_bucket
   FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   FIREBASE_APP_ID=your_app_id
   ```

### Running the Application

To run the application in development mode, use the following command:

```bash
npm run dev
```

This will start the development server, and you can view the application in your browser at `http://localhost:5173`.

### Building for Production

To build the application for production, use the following command:

```bash
npm run build
```

This will create a `dist` directory with the production build of your application.


## Deployment

The project is deployed at [moviesbyshruti.netlify.app/](https://moviesbyshruti.netlify.app/). If you encounter a "Page not found" error, paste the URL directly into your browser and try again.

## Contributing

If you want to contribute to this project, feel free to open a pull request or create an issue.

Feel free to adjust any details according to your project specifics.
