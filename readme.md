# Multi-Container Node.js and MongoDB Setup with Docker and Kubernetes
 his repository demonstrates how to set up a Node.js application with MongoDB using Docker and Kubernetes. The project includes multi-container deployment to ensure the services work seamlessly in a local and Kubernetes environment.

 # Steps to Run Locally with Docker
 1. Clone the Repository
 2. Build Docker Images
 3. Create a Docker Network
 4. Run MongoDB Container
 5. Run Node.js Container
 6. Access the Application

Open your browser and navigate to: http://localhost:3000

# Directory Structure
project-folder/

  |├── nodejs-app/
  |  
   |
   ├── Dockerfile


  |   └── index.js
  |
  ├── mongodb/
  |   |
  └── Dockerfile

  |├── mongo-deployment.yaml

  |└── nodejs-deployment.yaml