# 📝 todo_app

A modern, full-stack **To-Do App** built with the FARM stack (FastAPI, React, MongoDB, and Docker). This project demonstrates a robust architecture for building scalable, real-world web applications.

---

## 🚀 Features

- **FastAPI** backend for high-performance, async REST APIs
- **React** frontend with a clean, responsive UI
- **MongoDB** for flexible, document-based storage
- **Docker**-based development and deployment
- **Nginx** reverse proxy for production-ready serving
- Full CRUD for to-do lists and items
- Real-time UI updates
- Easy local development with `docker-compose`

---

## 🏗️ Project Structure
```
todo_app/
├── backend/           # FastAPI backend application
│   ├── app/           # Main FastAPI app code
│   └── Dockerfile     # Backend Dockerfile
├── frontend/          # React frontend application
│   ├── public/
│   ├── src/
├── nginx/             # Nginx configuration for production
│   └── nginx.conf
├── docker-compose.yml # Multi-service orchestration
├── .env (must be added)  # Example environment variables
└── README.md          # Project documentation
```

---

## 🛠️ Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

### Running Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/todo_app.git
    cd todo_app
    ```

2. Create and update the environment file as needed:
    ```bash
    touch .env
    ```

3. Start all services:
    ```bash
    docker-compose up --build
    ```

4. Access the app:
    - Frontend: 
    - API: [http://localhost:8000/docs](http://localhost:8000/docs)

---

## 📦 Deployment

- Update environment variables for production.
- Use the provided `nginx` config and Dockerfiles.
- Deploy with your preferred cloud provider or on-premise.

---

## 🤝 Contributing
- Contributions are welcome! Please open issues or submit pull requests.
---

## Disclaimer
This project is part of a tutorial that can be found here: [FARM Stack Course – Full Stack Development with FastAPI, React MongoDB](https://www.youtube.com/watch?v=PWG7NlUDVaA)