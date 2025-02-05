# ReplAI 🤖

ReplAI is a web application that enables users to generate text using generative AI models. The project provides a seamless user experience with a frontend built using React and Material UI, and a backend powered by Java, Spring Boot, and the Gemini API for text generation.

## Tech Stack 🛠️

- **Frontend:** React, Material UI 💻
- **Backend:** Java, Spring Boot ⚙️
- **AI Model Integration:** Gemini API 🤖

## Features ✨

- User-friendly interface for selecting a model and input text ✍️
- Real-time generation of text using the selected model ⏱️
- Option to save generated text to a file 💾
- Option to share generated text via email 📧
- Option to share generated text via social media 📱

## Project Structure 📂

The project consists of two main directories:

1. **replAi-frontend:** Contains the React-based frontend application using Material UI 🎨
2. **replAi-backend:** Contains the Spring Boot backend that integrates with the Gemini API for text generation ⚡

## Getting Started 🚀

To get started with ReplAI, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/masai-project/ReplAI.git
```

### 2. Install dependencies for the frontend

Navigate to the `replAi-frontend` folder and install the required dependencies:

```bash
cd replAi-frontend
npm install
```

### 3. Start the frontend application

Run the React development server:

```bash
npm start
```

The frontend will be available at `http://localhost:5173` 🌐.

### 4. Install dependencies for the backend

Navigate to the `replAi-backend` folder and build the Spring Boot application:

```bash
cd replAi-backend
./mvnw clean install
```

### 5. Start the backend server

Run the Spring Boot application:

```bash
./mvnw spring-boot:run
```

The backend will be available on `http://localhost:8080` 🌐.

## Contributing 🤝

Contributions are welcome! Feel free to fork the repository, make changes, and submit pull requests. Be sure to follow the coding standards and write tests for new features.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
