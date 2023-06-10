# SmartBrain

SmartBrain is a web application that uses machine learning to detect faces in images. It provides an intuitive user interface to upload images and analyze them for facial recognition.

## Features

- User authentication: Sign up and sign in functionality to securely access the application.
- Image upload: Upload images to be analyzed for facial recognition.
- Facial detection: Utilizes the Clarifai API to detect faces in the uploaded images.
- User profile: Displays user information, including name and entry count.
- Rank system: Tracks the number of images processed by the user.

## Installation

1. Clone the repository:

```shell
git clone https://github.com/LukeHSalmons/Smart-Brain.git
```

2. Navigate to the project directory:

```shell
cd smart-brain
```

3. Install dependencies:

```shell
npm install
```

4. Set up environment variables:
   - Create a `.env` file in the project root directory.
   - Add the following variables to the `.env` file:
     ```
     REACT_APP_CLARIFAI_API_KEY=your-clarifai-api-key
     REACT_APP_BACKEND_URL=your-backend-api-url
     ```

5. Start the application:

```shell
npm start
```

6. Open your browser and visit `http://localhost:3000` to access the application.

## Backend Integration

The SmartBrain frontend is designed to work with a corresponding backend API for user authentication and data management. Ensure that you have set up and configured the backend API correctly. Modify the `REACT_APP_BACKEND_URL` environment variable in the `.env` file to match your backend API URL.

For more information on setting up the backend API, please refer to the SmartBrain backend documentation.

## Dependencies

The following dependencies are used in this project:

- React: JavaScript library for building user interfaces.
- ParticlesBg: React component for particle backgrounds.
- Clarifai: JavaScript client library for the Clarifai API.
