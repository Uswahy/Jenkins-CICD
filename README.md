# Jenkins-CICD
This Jenkins pipeline is designed to automate the CI/CD (Continuous Integration/Continuous Deployment) process for a simple Node.js application that's containerized using Docker.
1. Cloning the Repository
The pipeline connects to your GitHub repository and pulls the latest code from the main branch. This ensures that Jenkins always builds the most up-to-date version of your project.

git branch: 'main', url: 'https://github.com/Uswahy/DockerWebApp.git'

✅Access the App in Browser:

http://localhost:4000

⚙️ Jenkins CI/CD Pipeline Setup
✅ Requirements
Jenkins installed and running (http://localhost:8080)

✅Docker installed and accessible by Jenkins

✅Git plugin installed in Jenkins

✅Already exist Jenkinsfile in DockerWebApp

🧪 Steps to Create Jenkins Pipeline
Open Jenkins dashboard

Click New Item → enter name(DockerWebApp-CICD) → select Pipeline → OK

Under Pipeline Configuration:

Select: Pipeline script from SCM

SCM: Git
✅Paste this gitrepo link

Repo URL: https://github.com/Uswahy/DockerWebApp.git

✅change branch

Branch: main

✅Apply and Save 
✅click Build Now
✅Your Node.js app will now automatically build and run in Docker via Jenkins
✅see console output for failure/success of deploying pipeline.




