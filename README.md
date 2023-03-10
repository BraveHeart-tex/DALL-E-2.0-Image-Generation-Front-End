# AI Image Generation Application

This application utilizes OpenAI's DALL-E 2 API to generate images based on user prompts. The frontend is built with React, TailwindCSS and React-Router-Dom. The backend is built with Node.js, Express.js, Cloudinary for image upload and MongoDB with Mongoose.

![Application live demo](./example.png)

## Features

- Generate unique images by providing a prompt
- Share generated images with the community
- Download generated images to your device

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- Cloudinary account
- OpenAI API key (Requires an OpenAI account)

### Installation

1. Clone the repository

```
git clone https://github.com/BraveHeart-tex/DALL-E-2.0-Image-Generation-Front-End
```

2. Inside the client folder, install dependencies

```
npm install or yarn add
```

3. Clone the backend repo. You can checkout the backend repository from <a href="https://github.com/BraveHeart-tex/DALL-E-2.0-Image-Generation-Back-End" target=_blank>here</a>.

```
git clone https://github.com/BraveHeart-tex/DALL-E-2.0-Image-Generation-Back-End
```


4. Create a .env file in the root directory with the following variables. .env file should be created in the root of the server folder.

```
MONGODB_URL="YOUR URL"
OPENAI_API_KEY="YOUR KEY"
CLOUDINARY_CLOUD_NAME="YOUR CLOUD NAME"
CLOUDINARY_API_KEY="YOUR API KEY"
CLOUDINARY_API_SECRET="YOUR API SECRET"
```

5. Start the application (in the server)

```
npm start
```

6. Start the application (in the client)

```
npm run dev
```

## Built With

- React
- TailwindCSS
- React-Router-Dom
- Node.js
- Express.js
- Cloudinary
- MongoDB
- Mongoose
<hr>

# Author

- Bora KARACA
