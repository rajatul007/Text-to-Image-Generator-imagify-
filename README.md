# 🎨 Imagify — Text to Image Generator

Imagify is a web-based **AI Text-to-Image Generator** that transforms your text prompts into AI-generated images.

Users can enter a creative prompt, generate an image, and explore AI-generated visuals through a simple and user-friendly interface.

## ✨ Features

* 🖼️ Generate images from text prompts
* 🤖 AI-powered image generation
* 👤 User authentication
* 📱 Responsive and modern UI
* 🔐 Secure backend API
* ☁️ Image generation and processing through backend services
* ⚡ Fast and easy-to-use interface

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript
* CSS
* HTML

### Backend

* Node.js
* Express.js
* REST API

### Database & Services

* MongoDB
* AI Image Generation API
* Authentication services

## 📁 Project Structure

```text
imagify/
│
├── client/                 # Frontend application
│
├── server/                 # Backend application
│   ├── routes/
│   │   ├── imageRoutes.js
│   │   └── userRoutes.js
│   │
│   ├── server.js
│   ├── package.json
│   └── vercel.json
│
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rajatul007/Text-to-Image-Generator-imagify-.git
```

### 2. Navigate to the project

```bash
cd Text-to-Image-Generator-imagify-
```

### 3. Install frontend dependencies

```bash
npm install
```

### 4. Install backend dependencies

```bash
cd server
npm install
```

### 5. Configure environment variables

Create a `.env` file inside the `server` directory:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
IMAGE_API_KEY=your_image_generation_api_key
```

> **Never commit your `.env` file or API keys to GitHub.**

### 6. Run the backend

```bash
cd server
npm run dev
```

### 7. Run the frontend

From the project root:

```bash
npm run dev
```

## 🔐 Environment Variables

The application may require environment variables for:

* MongoDB connection
* Authentication
* AI image generation API
* Other backend configuration

Keep all secret keys inside `.env` and add `.env` to `.gitignore`.

## 📸 How It Works

1. Enter a text prompt.
2. Submit the prompt to Imagify.
3. The backend processes the request.
4. The AI image generation service generates the image.
5. The generated image is displayed to the user.

## 🔮 Future Improvements

* Image history
* Download generated images
* Multiple image styles
* Image-to-image generation
* User profile and gallery
* Improved prompt suggestions
* Image sharing
* Additional AI models

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push your branch.
6. Open a Pull Request.

## 📄 License

This project is intended for educational and development purposes.
