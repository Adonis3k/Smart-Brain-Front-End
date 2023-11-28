# Smart-Brain

Smart-Brain is a React-based image recognition application that utilizes Clarifai's API. This app allows users to upload images, detect faces, and manage user profiles.

## Key Features

- Image input for face detection
- User registration and authentication
- Face detection with bounding box display
- User profile management
- Integration with Clarifai's API for accurate face detection

## Key Contributions

- Utilized React components to create a seamless user interface with features for image input, user registration, and authentication.
- Integrated Clarifai's API for accurate face detection and implemented logic to display bounding boxes around detected faces.
- Implemented state management to track user sessions, manage user profiles, and update entry counts upon successful image submissions.
- Employed project management methodologies to organize the development process, meet milestones, and ensure application functionality.

## Technical Skills Utilized

- React.js
- Clarifai API integration
- State management
- Frontend UI/UX design
- Fetch API for server communication

## Getting Started

1. Clone this repository
2. Run `npm install`
3. Run `npm start`
4. Add your own Clarifai API key in `controllers/image.js` to connect to Clarifai API
5. Add your own database credentials to `server.js` on line 12
6. Get your Clarifai API key [here](CLARIFAI_API_KEY_LINK)

**Note**: Use PostgreSQL instead of MySQL for this codebase.

## Usage

Ensure you have the necessary dependencies installed and configured. Follow the steps in the 'Getting Started' section to set up the application locally. You can then access the application on your local server.

