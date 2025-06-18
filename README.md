# CI-CD_1
Cloud-Native CI/CD Pipeline for NodeJS application using AWS services.
1️⃣ GitHub Repository: Stores source code (server.js, package.json, Dockerfile, buildspec.yml) to define dependencies and application logic. 
2️⃣ AWS CodePipeline: Monitors GitHub for updates and triggers the CI/CD process. 
3️⃣ AWS CodeBuild: Builds the application, installs dependencies (npm install from package.json), and creates a Docker image. 
4️⃣ Amazon ECR: Stores the latest container images for deployment. 5️⃣ AWS Fargate (ECS): Runs the containerized app, handling orchestration without server management. 
6️⃣ Task Definition: Configures port mapping, environment settings, and ECR image references. 
7️⃣ Application Load Balancer (ALB): Routes traffic to ECS tasks, ensuring availability. 
8️⃣ IAM Roles & Security Groups: Define permissions and secure deployment with restricted access. 
9️⃣ AWS S3 (Artifacts Storage): Stores build artifacts like buildspec.yml. 
🔟 Deployment Automation: Ensures efficient, scalable, and repeatable software delivery.
Danks.
