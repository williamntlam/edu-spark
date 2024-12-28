# EduSpark

**TODO**: The implementation of EduSpark is still in the planning phase. Development has yet to begin.

EduSpark is an intelligent learning companion that processes lecture videos, notes, and PowerPoints to generate concise summaries and flashcards. Powered by Angular for the frontend, Nest.js for the backend, Docker for containerization, and AWS cloud computing services for scalability, EduSpark makes studying smarter and more efficient.

## Features
- Upload lecture materials (videos, notes, PowerPoints).
- Automatically generate concise summaries.
- Create flashcards for efficient learning.
- Intuitive and responsive user interface built with Angular.
- Scalable backend powered by Nest.js.
- Cloud-based storage and processing leveraging AWS.

## Tech Stack
### Frontend
- **Framework**: Angular
- **Styling**: Tailwind CSS (or your preferred CSS framework)
- **State Management**: NgRx (if needed for complex state handling)

### Backend
- **Framework**: Nest.js
- **Database**: AWS RDS (PostgreSQL)
- **Authentication**: JSON Web Tokens (JWT) or AWS Cognito
- **APIs**: RESTful or GraphQL APIs

### Cloud Computing
- **Storage**: AWS S3 for storing uploaded files
- **Processing**: AWS Lambda for processing lecture materials
- **Video and Audio Processing**: Amazon Transcribe for audio transcription and Amazon Textract for extracting text from documents.
- **Image and Object Recognition**: Amazon Rekognition for analyzing images and detecting objects, text, or scenes.
- **Database**: AWS RDS for structured data storage
- **Deployment**: AWS Elastic Beanstalk or AWS ECS for hosting the backend
- **Monitoring**: AWS CloudWatch for application logs and metrics

### Containerization
- **Docker**: Containerize both the frontend and backend for consistent deployment across environments.
- **Docker Compose**: Orchestrate multi-container setups during development.

## Installation

### Prerequisites
1. Node.js (version 16 or later)
2. Angular CLI
3. Nest CLI
4. Docker and Docker Compose
5. AWS CLI configured with appropriate permissions

### Frontend Setup
```bash
cd frontend
npm install
ng serve
```
Access the Angular frontend at `http://localhost:4200`.

### Backend Setup
```bash
cd backend
npm install
npm run start:dev
```
The backend will be available at `http://localhost:3000`.

### Docker Setup
#### Build and Run Containers
1. Build the Docker containers for the frontend and backend:
```bash
docker-compose build
```
2. Start the containers:
```bash
docker-compose up
```
3. Access the services:
   - Frontend: `http://localhost:4200`
   - Backend: `http://localhost:3000`

### AWS Configuration
1. Configure an S3 bucket for file uploads.
2. Set up an RDS PostgreSQL database.
3. Deploy Lambda functions for processing videos, notes, and PowerPoints.
4. Use Amazon Transcribe for audio transcription and Amazon Textract for extracting text from documents.
5. Use Amazon Rekognition for image analysis, including detecting objects and extracting text from images.
6. Configure environment variables for AWS services in both the frontend and backend.

## Development Workflow
- **Frontend**: Develop new components, services, and modules using Angular CLI.
- **Backend**: Create and extend modules, controllers, and services in Nest.js.
- **Integration**: Use RESTful APIs or GraphQL to connect the frontend and backend.
- **Containerization**: Use Docker to build and test isolated environments.
- **Deployment**: Use AWS CLI or CI/CD pipelines to deploy updates to the cloud.

## Current Status
**NOT STARTED**
- The implementation is still in the planning phase. Development is yet to begin.
- 
## License
This project is licensed under the MIT License. See the LICENSE file for details.
