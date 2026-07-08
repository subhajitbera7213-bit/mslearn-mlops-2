# Azure Machine Learning MLOps Pipeline using GitHub Actions

## Project Overview

This project demonstrates an end-to-end Machine Learning Operations (MLOps) workflow using Microsoft Azure Machine Learning and GitHub Actions.

The objective of the project is to automate machine learning model training through Continuous Integration (CI), making the workflow reproducible, scalable, and cloud-native.

The project is based on Microsoft's Azure Machine Learning MLOps learning path and has been customized by configuring Azure resources, GitHub Actions, and automated training pipelines.

---

## Features

- Azure Machine Learning Workspace integration
- GitHub Actions CI pipeline
- Automated model training
- Pull Request triggered workflow
- Azure CLI integration
- Service Principal authentication
- Reproducible ML workflow
- Version-controlled machine learning project

---

## Project Architecture

```
Developer
     │
     ▼
GitHub Repository
     │
     ▼
GitHub Actions Workflow
     │
     ▼
Azure Machine Learning
     │
     ▼
Training Job
     │
     ▼
Model Registration & Logs
```

---

## Technologies Used

- Python
- Azure Machine Learning
- Azure CLI
- GitHub Actions
- YAML
- Git
- GitHub
- MLflow
- VS Code

---

## Workflow

1. Push code to GitHub.
2. Create a Pull Request.
3. GitHub Actions automatically starts.
4. Azure authenticates using a Service Principal.
5. Azure Machine Learning submits a training job.
6. Model is trained in Azure Compute.
7. Training logs are generated.
8. Workflow completes successfully.

---

## Repository Structure

```
.
├── .github/
│   └── workflows/
├── src/
├── data/
├── components/
├── pipelines/
├── environment/
├── infra/
└── README.md
```

---

## GitHub Actions

This project uses GitHub Actions to automate machine learning workflows.

The pipeline performs:

- Environment validation
- Azure authentication
- Azure ML job submission
- Automated model training
- Workflow logging

---

## Learning Outcomes

Through this project, I learned:

- MLOps fundamentals
- Continuous Integration (CI)
- Azure Machine Learning
- GitHub Actions
- Azure CLI
- Cloud authentication using Service Principals
- ML workflow automation
- Version control for ML projects

---

## Screenshots

Add screenshots of:

- Azure ML Workspace
- GitHub Actions Success
- Pull Request
- Azure Training Job
- Training Logs
- Registered Model (if available)

---

## Future Improvements

- Continuous Deployment (CD)
- Model deployment to Azure Online Endpoint
- Model monitoring
- Data drift monitoring
- Automated retraining
- Unit testing
- Model version comparison

---

## Author

**Subhajit Bera**

B.Tech Student

Machine Learning | Azure Machine Learning | MLOps | GitHub Actions

GitHub:
https://github.com/subhajitbera7213-bit

LinkedIn:
(Add your LinkedIn profile)
