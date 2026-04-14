DevOps CI/CD Project – Node.js & React Application
 Project Description
 
This project demonstrates a complete DevOps pipeline by building, testing, and deploying a Node.js and React application using Jenkins.
The application is a simple web app that displays a page with a "Learn React" link. The main goal is to automate the software delivery process using CI/CD practices.
   Tech Stack
   
Frontend: React.js
Backend: Node.js
CI/CD: Jenkins
Version Control: Git & GitHub
Containerization: Docker
Cloud Platform: AWS EC2 (Ubuntu)
Monitoring: Prometheus, Grafana, Node Exporter
Automation: Bash Scripting, Cron Jobs
📂 Setup Instructions (Run Locally)
1. Clone Repository
git clone https://github.com/nihilbalu1231/capstone.git
cd capstone
2. Install Dependencies
npm install
3. Run Application
npm start
4. Access Application
Open your browser and go to:
http://localhost:3000
 Run Using Docker
Build Docker Image
docker build -t node-react-app .
Run Docker Container
docker run -d -p 3000:3000 node-react-app
CI/CD Pipeline Flow
Developer pushes code to GitHub
Jenkins automatically triggers the pipeline
Jenkins installs dependencies and builds the application
Docker image is created using Dockerfile
Docker image is pushed to Docker Hub
Jenkins connects to AWS EC2 instance via SSH
Application is deployed as a Docker container
Prometheus collects system metrics
Grafana displays monitoring dashboards

 Conclusion
 
This project demonstrates how DevOps tools like Jenkins, Docker, AWS, Prometheus, and Grafana work together to automate the software delivery lifecycle and enable continuous integration and deployment
