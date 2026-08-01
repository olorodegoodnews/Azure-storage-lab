# Azure-storage-lab
Hands-on Azure Storage lab based on Microsoft Learn. This project documents the creation and management of Azure Storage resources.

## Step 1 – Create an Azure Storage Account

### Objective

Create an Azure Storage Account to provide secure and scalable cloud storage for Azure services.

### Configuration

| Setting | Value |
|---------|-------|
| Resource Group | IAM-RBAC-Lab-RG |
| Performance | Standard |
| Redundancy | Locally Redundant Storage (LRS) |

### Why?

An Azure Storage Account is the foundation for Azure storage services such as Blob Storage, Azure Files, Queue Storage, and Table Storage.

### Result

The Azure Storage Account was successfully created.

### Screenshot

![](screenshots/01-storage-account-created.png.png)


---

## Step 2 – Create a Blob Container

### Objective

Create a Blob Container inside the Azure Storage Account to organize and store blob data.

### Configuration

| Setting | Value |
|---------|-------|
| Container Name | public |
| Access Level | Private (No anonymous access) |

### Why?

A Blob Container provides a logical way to organize files stored in Azure Blob Storage.

### Result

The Blob Container was successfully created and is ready to store blobs.

### Screenshot

![](screenshots/02-blob-container-created.png.png)



## Step 3 – Upload a Blob

### Objective

Upload a file to the Blob Container to verify that the Storage Account is ready to store data.

### Configuration

| Setting | Value |
|---------|-------|
| Storage Service | Azure Blob Storage |
| Container | goodnews001 |
| Uploaded File | Tryhackme Soc Level 1 Certificate |

### Why?

Uploading a blob confirms that the Blob Container is working correctly and can securely store files.

### Result

The file was successfully uploaded to the Blob Container.

### Screenshot

![](screenshots/03-blob-uploaded.png.png)
