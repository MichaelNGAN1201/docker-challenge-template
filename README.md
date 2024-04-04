Docker Challenges Learning Experience

This repository documents my learning experience and findings while completing Docker challenges. Through these challenges, I aimed to gain a deeper understanding of Docker, its applications, and related concepts such as Docker Compose. Below, I outline my journey and reflections on each challenge.

Challenge 1: Simple Web Server for Static Web Pages
Goals Achieved:
Understanding the basics of Docker.
Building a Docker image.
Running a container and viewing the results on the browser.
Publishing Dockerfile and related files on GitHub.
Steps Taken:
Created a new folder challenge1.
Added a public folder containing assets.
Developed an index.html file with personal information.
Constructed a Dockerfile to utilize NGinx for serving pages.
Built the Docker image.
Executed Docker with appropriate parameters.
Committed Dockerfile and public folder to the remote repository.
Verified the application and captured screenshots of the running server and served page.
Outcomes:
Successfully accessed a homepage with personal information at http://localhost:8080/.

Challenge 2: Creating a Dynamic Application
Goals Achieved:
Introduction to Docker Compose.
Building a Dockerfile for a NodeJS application.
Running a dynamic application on Docker.
Steps Taken:
Utilized the challenge2 folder.
Added files from challenge2.zip to the root.
Developed a Dockerfile for building the server container.
Created a Docker Compose file with NGinx and the API server.
Ensured proper functioning of all services.
Tested endpoints like http://localhost:8080/api/books.
Rectified any unexpected outcomes.
Committed and pushed all files to the remote repository.
Outcomes:
Successfully accessed JSON messages at specified API endpoints.

Findings and Reflections:
Docker is a powerful tool for containerization, simplifying application deployment.
Docker Compose streamlines the orchestration of multi-container applications.
Proficiency in writing Dockerfiles and Docker Compose files is essential for deploying complex applications.
Detailed documentation and thorough submissions are vital for knowledge sharing and reproducibility.
Through these challenges, I have gained practical experience in Docker and Docker Compose, which will prove invaluable in my future projects and endeavors.
