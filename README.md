# DevOps Project: Todo Python App with GitHub, Jenkins, SonarQube, Dependency Check, Docker, and Trivy

This project demonstrates the CI/CD pipeline for a Python-based Todo application, utilizing tools such as GitHub, Jenkins, SonarQube, Dependency Check, Docker, and Trivy. The application is containerized, scanned for vulnerabilities, and deployed to production.

![Project Architecture](https://github.com/user-attachments/assets/c99da0b6-d10f-4247-b9e5-854345c7e5c1)

## Jenkins Pipeline Setup

### Creating Jenkins Pipeline
![creating pipeline](https://github.com/user-attachments/assets/5bbd9228-ff04-4d31-a53b-8b492c89d00a)

### Writing the Pipeline Script
The pipeline script is available in the repository for automation of the build, test, and deploy processes.
![writing pipeline script](https://github.com/user-attachments/assets/be2624df-bfb4-4d0c-af35-649f8b12dbcc)

### Configuring Jenkins Credentials for SonarQube and Docker
![creds jenkins](https://github.com/user-attachments/assets/364da95f-40cb-4150-a40f-1f15e231237e)

## SonarQube Integration

### Running SonarQube using Docker on Port 9000
![sonar homepage](https://github.com/user-attachments/assets/8b4c1998-bf70-4317-a4de-91bba34979aa)

### Generating SonarQube Token for Jenkins Integration
![token sonar](https://github.com/user-attachments/assets/74c75dd7-e7c6-4dca-8dd6-481a24a7d429)

### Managing Jenkins Setup for SonarQube and Dependency Check
![manage jenkins sonar](https://github.com/user-attachments/assets/4c55672f-2fa4-4b59-9caf-cfe7407daa00)
![manage jenkins dp](https://github.com/user-attachments/assets/6ad51419-4701-413e-b8cc-e6a18a6adb55)

## Jenkins Build and Deployment

### Triggering the Jenkins Build
![buildnow](https://github.com/user-attachments/assets/eea5093d-7078-4b98-a4f4-e9c64e907e8a)

### Build Job Completion
![finished job](https://github.com/user-attachments/assets/eb902dd8-e519-4273-bfdf-24ee12252021)

### SonarQube Quality Analysis Result
The Jenkins build successfully passes the code analysis in SonarQube.
![sonar project ](https://github.com/user-attachments/assets/f3acd716-49e2-43c2-a2e2-a8cb79cce722)

## Docker Integration

### Uploading the Docker Image to DockerHub
![docker hub](https://github.com/user-attachments/assets/05f69716-435e-4e3c-b2a2-3630c1d028d2)

### Creating the Docker Image and Running the Container on Port 8000
![Docker Images](https://github.com/user-attachments/assets/b49c3433-2ccb-4afa-ab26-7e52e6646e42)
![Docker PS](https://github.com/user-attachments/assets/d72e0826-7092-4802-9fac-9d51d54484f5)

## Testing

### Testing the Todo Application in the Browser
![testing todo](https://github.com/user-attachments/assets/64fc7d16-d13d-4272-afe5-4463be745754)
