# azure-dotnet-modernization
A cloud modernization project, including .NET containerization, Azure Container Registry (ACR), and Azure Container Instances (ACI).



# Cloud Portfolio & Infrastructure Projects

Welcome to my professional GitHub portfolio! This repository highlights my hands-on experience with cloud engineering, containerization, and modernizing legacy applications using **Microsoft Azure**.

---

## 🚀 Featured Project: Azure .NET Container Modernization

### Overview
This project demonstrates the transition of legacy monolithic systems into lightweight, cost-effective containerized microservices. A custom .NET web application was containerized locally using Docker, stored securely in **Azure Container Registry (ACR)**, and deployed globally via **Azure Container Instances (ACI)**.

### Architecture Workflow

### Key Technical Highlights
* **Local Development & Build:** Initialized a .NET web application, customized the UI with tracking markers, and executed local builds binding to port 8080.
* **Multi-Stage Containerization:** Engineered a secure multi-stage `Dockerfile` leveraging official Microsoft .NET 10.0 SDK and ASP.NET runtime base images to minimize final image size.
* **Registry Management:** Authenticated and pushed versioned container images into a private **Azure Container Registry (ACR)**.
* **Serverless Deployment:** Deployed the container live as an **Azure Container Instance (ACI)**, generating a public Fully Qualified Domain Name (FQDN) endpoint (`webapp-271062825.newzealandnorth.azurecontainer.io`).

### Architecture Diagram
Below is the architectural blueprint illustrating the deployment workflow:
