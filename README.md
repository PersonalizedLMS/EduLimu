# EduLimu

## AI-Powered Personalized E-Learning System

EduLimu is an innovative AI-driven platform that delivers a personalized learning experience tailored to each student's preferences, progress, and performance. By leveraging state-of-the-art artificial intelligence, the platform dynamically generates adaptive quizzes, provides real-time feedback, and includes an AI tutor to enhance learning outcomes. Designed for individuals and educational institutions, EduLimu aims to revolutionize digital education by making learning more engaging, efficient, and accessible.

## Key Features

- **Institution Integration:** Designed for seamless integration with schools, colleges, and universities.
- **Adaptive Quizzes & Assessments:** AI-generated quizzes that adjust difficulty based on student progress.
- **Personalized Learning Paths:** AI-driven recommendations based on students' learning habits and performance.
- **AI Tutor:** Virtual assistant providing real-time support and answering student queries.
- **Real-Time Feedback:** Instant AI-powered feedback to help students improve their understanding.

## Technology Stack

EduLimu is built with cutting-edge technologies to ensure performance, scalability, and security.

### **Frontend:**

- ReactJS
- Tailwind CSS

### **Backend:**

- Django (for AI-powered functionalities and content management)
- NodeJS (RESTful API and business logic)
- Inngest (Workflow automation)
- Kafka (Messaging & Event Handling)

### **Database:**

- PostgreSQL-based database for storing user data, learning resources, and performance metrics.

### **AI & Machine Learning:**

- TensorFlow / PyTorch (AI-driven recommendations and adaptive quizzes)
- NLP Models (AI Tutor and real-time feedback analysis)
- Third-party AI APIs (OpenAI, Gemini, DeepSeek)

### **Infrastructure & Deployment:**

- Docker & Kubernetes (Containerized deployment and scalability)
- CI/CD Pipeline (GitHub Actions for continuous integration and deployment)

## Running the App

### **First Install Dependencies**

```sh
  npm install
  #or
  yarn install
  #or
  pnpm install
```

### **Install Backend Dependencies**

```sh
  cd ../backend
  pip install -r requirements.txt  # Django dependencies
  npm install  # NodeJS dependencies
```

### **Run the Application**

```sh
  npm start  # Start the backend server
  npm run dev  # Start the frontend
```

## Technical Architecture

EduLimu is designed with a microservices architecture to ensure scalability, modularity, and maintainability. The system comprises multiple services, including the frontend, backend API, AI services, and database, all communicating via Kafka messaging. This architecture enables seamless integration of new features, such as the AI tutor, adaptive quizzes, and personalized learning paths.

### **Architecture Diagram:**

```
User → React Frontend → Node.js API → Kafka → AI Services → Database → Response to User
```

## Demo & Screenshots

**Live Demo:** [EduLimu Demo](https://edulimu.app) *(Coming Soon!)*  
**Screenshots:** Uploading PDFs, AI recommendations, quizzes *(To be added)*

## Contribution Guide

We welcome contributions from the open-source community! Here’s how you can help:

1. **Fork the Repository**
2. **Create a Feature Branch**

    ```sh
    git checkout -b feature-new-ai-tutor
    ```

3. **Commit Your Changes**

    ```sh
    git commit -m "Added advanced AI tutor functionality"
    ```

4. **Push to GitHub & Open a Pull Request**

    ```sh
    git push origin feature-new-ai-tutor
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

A special thanks to all contributors and the open-source community for their support!

---

**Have an idea to improve EduLimu?** Open an issue or contribute to the project!

**Meet Our Team**\
| [James Moseti](https://github.com/james-moseti) | [Christine Awuor](https://github.com/OdegiChristine) | [Adrian Baraka](https://github.com/adrianbaraka) | [Gift Nestah](https://github.com/PantheraNestah) |
