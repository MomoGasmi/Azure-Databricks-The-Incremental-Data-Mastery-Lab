

# 🚀 Azure Databricks: Incremental Data Mastery Lab

## 🏗️ Project Architecture
This diagram outlines the end-to-end flow from raw data ingestion to Power BI reporting.
![Project Architecture Diagram](images/project_Architecture.jpg)

---

## 📋 Prerequisites
Before you begin, ensure you have:
* An active **Azure Account**.
* **VS Code** installed with the Azure & Databricks extensions.
  ![Databricks Extensions](images/DataBricks_Extensions_installed.jpg)
* A created **Databricks Workspace**.

---

## 🛠️ Step 1: Azure Environment Setup

### 1. Resource Group Creation
Log in to the [Azure Portal](https://portal.azure.com) and create a **Resource Group** named `Databricks_project1`. 

| Action | Visual Reference |
| :--- | :--- |
| **Defining the Group** | ![Creating Resource Group](images/create_Resources_Group.png) |
| **Successful Deployment** | ![Created Resource Group](images/Created_Resources_Group.png) |

### 2. Storage Configuration
Deploy a **Storage Account (ADLS Gen2)** with "Hierarchical Namespace" enabled. This acts as our Bronze, Silver, and Gold storage layers.