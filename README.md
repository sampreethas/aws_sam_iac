# AWS SAM (Serverless Application Model) Demo App  

This project demonstrates how to **build, deploy, and sync a serverless application** using **AWS Serverless Application Model (SAM)**.  

Features:  
-  **Define infrastructure as code**  
-  **Deploy AWS Lambda functions**  
-  **Sync changes in real-time**  

---

##  Features  

-  **Quick Setup** – Start with `sam init`  
-  **Local Testing** – Test Lambda before deploying  
-  **Fast Syncing** – Update AWS resources with `sam sync`  
-  **Full Deployment** – Use `sam deploy` for production  

---

##  Prerequisites  

Before you begin, ensure you have:  

- **AWS CLI** → [Install Here](https://aws.amazon.com/cli/)  
- **AWS SAM CLI** → [Install Here](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html)  
- **Python 3.8+** → [Download Here](https://www.python.org/downloads/)  
- **Docker** (for local testing) → [Install Here](https://www.docker.com/get-started)  

---

## Getting Started  

### 1. Initialize a New SAM Project  
Run the following command to initialize a new AWS SAM project:
```sh
sam init
```
### 2 Build the project  
Run the following command to build the project:
```sh
sam build
```
### 3. Deploy the project  
Run the following command to deploy the project:
```sh
sam deploy --guided
```
sync project using: 
```sh
sam sync --config-file samconfig.toml
```

## Outputs

<img width="773" alt="Screenshot 2025-02-15 at 11 38 24 PM" src="https://github.com/user-attachments/assets/7f1dba79-898d-4777-a783-d2c53a3bfeb2" />

Stack created on AWS Console:

<img width="1068" alt="Screenshot 2025-02-15 at 11 42 42 PM" src="https://github.com/user-attachments/assets/9988fe76-24f6-4d9b-928a-19175b8e7f90" />


