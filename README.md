<!-- vscode-markdown-toc -->

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

# 9Kicks

## Table of Contents

- 1. [Description](#Description)
- 2. [Team Members](#TeamMembers)
- 3. [Project Structure](#ProjectStructure)
  - 3.1. [Frontend](#Frontend)
  - 3.2. [Backend](#Backend)
  - 3.3. [Infrastructure](#Infrastructure)

## 1. <a name='Description'></a>Description

This is a group project for the course CSCI3100 Software Engineering. The project is a online sneaker shopping platform. The platform is designed for sneaker lovers to buy and sell sneakers. The platform is built with:

- Frontend: SvelteKit
- Backend:
  - Kotlin with Spring Boot
  - Go with Gin
- Database:
  - DynamoDB
  - OpenSearch
- CI/CD: GitHub Actions
- Deployment: AWS with Terraform

## 2. <a name='TeamMembers'></a>Team Members

- Cheng Yu Shing 1155158488
- Ho Hon Lung 1155151893
- Lam Chi Fung 1155159343
- Lo Hoa Tsun 1155158762
- Wu Ka Tung 1155157687

## 3. <a name='ProjectStructure'></a>Project Structure

The project is divided into 3 main parts: frontend, backend, and infrastructure.

### 3.1. <a name='Frontend'></a>Frontend

The user-facing part of the project is located in the `frontend` directory.

And the admin-facing part of the project is located in the `admin-panel` directory.

These two parts are built with SvelteKit.

For the setup of the frontend, please refer to

- [frontend/README.md](https://github.com/9KicksXCUmart/9KicksShop/blob/main/README.md)
- [admin-panel/README.md](https://github.com/9KicksXCUmart/9Kicks-Admin-Panel/blob/main/README.md)

### 3.2. <a name='Backend'></a>Backend

The backend is composed of two separate services: `go-backend` and `kotlin-backend`.

For the setup of the backend, please refer to

- [go-backend/README.md](https://github.com/9KicksXCUmart/9Kicks-Mircoservices-Go/blob/main/README.md)
- [kotlin-backend/README.md](https://github.com/9KicksXCUmart/9Kicks-Mircoservices-Kotlin/blob/main/README.md)

### 3.3. <a name='Infrastructure'></a>Infrastructure

The infrastructure is managed by Terraform. The Terraform configuration is located in the `IaC` directory.

For the setup of the infrastructure, please refer to

- [IaC/README.md](https://github.com/9KicksXCUmart/9Kicks-IaC/blob/main/README.md)
