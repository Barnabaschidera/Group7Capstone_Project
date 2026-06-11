# CapstoneG7 Web Application

## Project Overview

CapstoneG7 Web Application is a cloud-hosted Node.js web application developed as part of the TechCrush Cohort 6 Capstone Project.

The project demonstrates the deployment of a web application to Microsoft Azure App Service using GitHub Actions for Continuous Integration and Continuous Deployment (CI/CD).

The application consists of a Home Page and an About Page and showcases modern DevOps practices, cloud deployment, and collaborative software development.

---

## Problem Statement

Manual deployment processes often result in configuration inconsistencies, downtime, and human errors. Organizations require reliable and automated deployment pipelines that ensure applications are delivered efficiently and consistently.

This project addresses these challenges by implementing a cloud-hosted web application with automated deployment through GitHub Actions and Microsoft Azure App Service.

---

## Project Objectives

- Develop a functional Node.js web application.
- Create responsive frontend pages using HTML and CSS.
- Deploy the application to Microsoft Azure App Service.
- Implement CI/CD using GitHub Actions.
- Configure environment variables securely.
- Demonstrate cloud deployment best practices.
- Promote collaborative software development.

---

## Application Type

Multi-Page Informational Website (Landing Page)

### Features

- Home Page
- About Page
- Page Navigation
- Azure Cloud Hosting
- Automated Deployment
- GitHub Actions CI/CD Pipeline

---

## Technology Stack

| Component | Technology |
|------------|------------|
| Frontend | HTML5, CSS3 |
| Backend | Node.js, Express.js |
| Version Control | Git & GitHub |
| Cloud Platform | Microsoft Azure App Service |
| Automation | GitHub Actions |
| Configuration | Azure Environment Variables |
| Infrastructure Tool | Azure CLI |

---

## Team Members

| Team Member | Responsibility |
|------------|---------------|
| Ayandele | Frontend Development |
| Ganiu | Backend Development |
| Obinna | Azure Infrastructure Setup |
| Barnabas | CI/CD Pipeline Configuration |
| Rita  | Deployment Slot Investigation & Testing |
| Roi | Documentation & Presentation |

---

## Project Architecture

GitHub Repository

↓

GitHub Actions (CI/CD)

↓

Azure App Service

↓

Live Website

---

## Installation Guide

### Clone the Repository

```bash
git clone https://github.com/Barnabaschidera/Group7Capstone_Project
```

### Navigate into the Project Directory

```bash
cd Group7Capstone_Project
```

### Install Dependencies

```bash
npm install
```

---

## Running the Application Locally

Start the application:

```bash
npm start
```

Open your browser and visit:

```text
http://localhost:3000
```

---

## Deployment Process

The application is automatically deployed through GitHub Actions.

### Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions workflow is triggered.
3. Dependencies are installed.
4. Application is built.
5. Application is deployed to Azure App Service.
6. Deployment status is verified.

---

## Environment Variables

Azure App Service manages application environment variables securely.

Example:

```javascript
process.env.NODE_ENV
```

---

## Deployment Slot Configuration

The project requirement included the creation of a deployment slot.

During implementation, Azure displayed the message:

> Upgrade to a standard or premium plan to add slots.

Deployment slots are only supported on Standard and Premium App Service Plans.

Due to Azure Free Trial limitations, deployment slots could not be implemented.

---

## Live Application URL

https://capstoneg7webapp-f8hhdbgtcvamcxdp.southafricanorth-01.azurewebsites.net/

---

## Results and Outcomes

The project successfully achieved:

- Functional Node.js Web Application
- Azure Cloud Deployment
- GitHub Actions CI/CD Automation
- Environment Variables Configuration
- Publicly Accessible Website
- Team Collaboration and Role Distribution

---

## Challenges Encountered

- Azure quota limitations
- Azure Free Trial restrictions
- Deployment slot unavailability
- Initial deployment configuration challenges

---

## Solutions Implemented

- Leveraged Azure Free Trial resources
- Automated deployments using GitHub Actions
- Successfully deployed application to Azure App Service
- Documented deployment slot limitations

---

## Future Improvements

- Upgrade to Azure Standard Plan
- Implement Deployment Slots
- Add Database Integration
- Add Authentication and Authorization
- Implement Automated Testing
- Improve User Interface Design

---

## Conclusion

This project successfully demonstrated the deployment of a Node.js web application to Microsoft Azure App Service using GitHub Actions for Continuous Integration and Continuous Deployment.

The team collaboratively implemented frontend development, backend development, cloud infrastructure, CI/CD automation, and deployment documentation while gaining practical experience in DevOps and cloud computing.

