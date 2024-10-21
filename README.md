# AI Image Generator

An AI-powered image generator built with the MERN (MongoDB, Express, React, Node.js) stack and Hugging Face's models for generating images from text inputs, and Cloudinary for image storage.

## Features

- Generate images from text prompts using Hugging Face's API.
- Store generated images in Cloudinary for easy access and sharing.
- User authentication and image history management.
- Frontend built with React and styled using MaterialUI.
- Backend API with Node.js and Express to handle requests.
- MongoDB for storing user data and image generation history.

## Tech Stack

 ### Frontend:
- **React.js** – for building dynamic user interfaces
- **Material UI** – for a polished and responsive UI
- **Axios** – for handling API requests

 ### Backend:
- **Node.js** with **Express.js** – for creating a RESTful API
- **MongoDB** – for database management (image and user data)
- **AI Model**: Hugging Face (for text-to-image generation)
- **Image Storage**: Cloudinary
- **API Integration**: Hugging Face, Cloudinary
  
## Installation

 ### Prerequisites
 Make sure you have the following installed:
 - Node.js
 - MongoDB
 - Git

 ### Setup

 1. Clone the repository:

    git clone https://github.com/sanjanasingh1818/ai-image-generator.git
   
 2. Install the required dependencies for both the frontend and backend:

    Install backend dependencies:
     cd backend
     npm install

    Install frontend dependencies:
     cd frontend
     npm install

 4. Set up environment variables:

    Create a .env file in both the backend and frontend directories with the following variables:
   
  ## Backend:
   - MONGO_URI=your_mongodb_connection_string
   - CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   - CLOUDINARY_API_KEY=your_cloudinary_api_key
   - CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   - HUGGING_FACE_API_KEY=your_hugging_face_api_key
   
  ## Frontend:
     REACT_APP_API_URL=http://localhost:5000

 4. Start the development servers:

    ## Backend:
    cd backend
    
    npm start
   
    ## Frontend:
    cd frontend
    
    npm start
   
    The frontend should now be running on http://localhost:3000 and the backend on http://localhost:5000.

 # Usage
  
   1. Enter a text prompt (e.g., "A sunset over the mountains").
   2. Submit the prompt to generate an image using Hugging Face's AI model.   
   3. The generated image is stored in Cloudinary and displayed on the screen.

 # Dependencies

  ## Frontend:
   - React
   - Axios
   -  Material UI
  ## Backend:
   - Express
   - MongoDB
   - Cloudinary SDK
   - Hugging Face API

 # Screenshots 
  
  ![Screenshot (173)](https://github.com/user-attachments/assets/d4e6de0e-3317-4b3b-a9c3-a6357e6ca430)

  ![Screenshot (174)](https://github.com/user-attachments/assets/53030197-25c2-486a-bb48-eaa73fd190ed)


# License
   This project is licensed under the MIT License - see the LICENSE file for details.

   



