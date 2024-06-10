# PublicVersionGeminiProject
This is the public development repository for our final project (Ballmer's Peak) excluding all sensitive files needed to run.

**LINK TO OUR REPO:**  https://github.com/StephenR-20/DevVersionGeminiProject.git
Cloud Computing Final Project - Team Ballmer’s Peak 

 

Project Title: Image Feedback Provider

Group Members : 

Stephen Randall 

Jon Riklan 

Zi Han 

Ian Murday 

Adam Sheelar 



 

Overview: 

This is the final project for CS1660. The objective is to leverage Google Cloud 

Platform (GCP) services to build a cloud-based application that incorporates at least three different cloud services (i.e. Cloud Storage, Compute Engine, Cloud Run, 

BigQuery, etc). These services do not need to be limited to the ones covered in the 

course, and the project can be developed using any programming language or framework. Each team will be responsible for choosing a project idea, developing the application, 

and deploying it on GCP. 

Project Description: 

For our project we will be following the second project prompt: “Image Processing Service”. We created a web application that can take in a reference image as input and prompt Google Gemini to give the user feedback on how to improve the quality of the image. This application could be useful for editing purposes for photographers: understanding weakpoints in their images, lighting, contrast, focus points, etc.. 

The Cloud Services we levereged: 
- Buckets
- Loadbalancers
- Firebase (using Bucket)
- Dockerized our app
- Implemented CI/CD with github actions (creates a new Docker build automatically upon push or pull)


