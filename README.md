
📸 SnapShare - Photo Sharing Social Platform

SnapShare is a modern, full-stack photo sharing social media application that delivers an engaging user experience through a vibrant Angular-based UI. It enables users to post photos, like and comment on others' content, and interact in real-time — all while ensuring data security and performance.

------------------------------------------------------------

🚀 Key Features

- 📷 Photo upload and sharing
- ❤️ Like and comment on posts
- 🔐 Secure user authentication with JWT
- 👤 Role-based access with Spring Security
- 📡 Real-time data operations via RESTful APIs
- 🗄️ Efficient data handling using Spring Data JPA
- 🐳 Dockerized microservices
- ☸️ Kubernetes for container orchestration
- 🔄 CI/CD with GitHub Actions

------------------------------------------------------------

🧰 Tech Stack

Frontend: Angular 17, TypeScript, HTML/CSS
Backend: Spring Boot, Spring Security
Database: MySQL / PostgreSQL (configurable)
DevOps: Docker, Kubernetes
CI/CD: GitHub Actions

------------------------------------------------------------

📁 Project Structure

snapshare/
├── frontend/               # Angular 17 Frontend
├── backend/                # Spring Boot REST API
├── k8s/                    # Kubernetes Deployment Files
├── docker-compose.yml      # Docker Compose Configuration
└── README.md

------------------------------------------------------------

🏁 Getting Started

🔧 Prerequisites

- Java 17+
- Node.js & Angular CLI
- Maven
- Docker & Kubernetes
- Git

🚨 Clone the Repository

git clone https://github.com/anushgovekar18-ui/Snapshare.git
cd Snapshare

▶️ Run Backend

cd backend
mvn spring-boot:run

▶️ Run Frontend

cd frontend
npm install
ng serve

------------------------------------------------------------

🐳 Docker Deployment

docker-compose up --build

------------------------------------------------------------

☸️ Kubernetes Deployment

kubectl apply -f k8s/

------------------------------------------------------------

🛡️ Security

- JWT-based user authentication
- Password encryption with BCrypt
- Role-based API access control

------------------------------------------------------------

✅ CI/CD Pipeline

- GitHub Actions for automated build, test, and deploy
- Container images pushed to Docker Hub
- Kubernetes deployment through manifest files

------------------------------------------------------------

📃 License

This project is licensed under the MIT License.
See LICENSE file for details.

------------------------------------------------------------

🙋‍♂️ Author

Anush Govekar
GitHub: @anushgovekar18-ui

------------------------------------------------------------

📌 Status

✅ Active development
🚀 More features coming soon!
