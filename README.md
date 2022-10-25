# What is an Artifact Repository?
Storage of build artifacts produced by continuous integration and makes them available for automated deployment to different deployment environments Provides a central location Artifacts are applications built into a single file There are different artifact formats
Provides a central location
Artifacts are applications built into a single file
There are different artifact formats:
Artifact repository needs to support this specific format
Repository for each file/artifact type
![image](https://user-images.githubusercontent.com/99332618/197736690-bf734930-fecb-45cd-a535-0929e56dff4c.png)

# Public vs Private Artifact Repository Managers
![image](https://user-images.githubusercontent.com/99332618/197737049-33a1b539-f6f4-44d2-be26-3363491ec9c5.png)

# Nexus - Artifact Repository Manager
![image](https://user-images.githubusercontent.com/99332618/197737345-57df702c-74d2-45bb-bc25-fd334821baa3.png)

# Features of Repository Manager
Integration with LDAP
Flexible and powerful REST API for integration with other tools
Backup and Restore
Multi-Format Support (different file types - zip, tar, docker etc)
Metadata Tagging (labelling and tagging artifacts)
Cleanup Policies (automatically delete files that match condition)
Search functionality (across projects, artifact repos etc.)
User token support for system user authentication
![image](https://user-images.githubusercontent.com/99332618/197737770-71284dcd-91ad-492e-a22a-10ff89d6d549.png)

# Install and Run Nexus on Cloud Server - 1
Create Ubuntu Server (Droplet) - min 4GB RAM & 2 CPUs
Open SSH port 22
Install Java 8
Download and Install Nexus
Create "nexus" user and group - Best Practice: Run applications with own user

# Install and Run Nexus on Cloud Server - 2
![image](https://user-images.githubusercontent.com/99332618/197739325-7738c3c6-a14d-4e13-95ab-ee28cea364d0.png)

# Install and Run Nexus on Cloud Server - 3
![image](https://user-images.githubusercontent.com/99332618/197739613-3c1f30a8-0652-4a62-962c-2f21a1fcc897.png)

# Install and Run Nexus on Cloud Server - 4
![image](https://user-images.githubusercontent.com/99332618/197740076-c5f22c21-bd0e-41e6-81cb-02aa4d788c7b.png)

# Install and Run Nexus on Cloud Server - 5
![image](https://user-images.githubusercontent.com/99332618/197740323-7332033b-ad2e-4f1a-809f-cfb96d8b665d.png)
![image](https://user-images.githubusercontent.com/99332618/197740459-f3aeb2e6-b3dc-4c82-9320-9f1c2f573b98.png)

# Overview of Nexus
## Login & Default Repositories
![image](https://user-images.githubusercontent.com/99332618/197740894-07f4ad7f-772c-4609-9a36-509d08bc80f2.png)

# Repository Types & Formats
![image](https://user-images.githubusercontent.com/99332618/197741239-1eec78af-42f1-4614-85ac-839960aed1f6.png)

# Publish artifact to repository
You can push or "PUBLISH" artifacts to Nexus with different tools:
Using built-in commands of build tools, like Maven or Gradle.
For that, you need to configure each build tool with Nexus credentials and address.
![image](https://user-images.githubusercontent.com/99332618/197741675-f3b7809a-b645-4620-9b8d-4b8b24102b21.png)

# Nexus REST API
![image](https://user-images.githubusercontent.com/99332618/197741903-c9890cab-b919-45de-a968-565e4b284c7a.png)

# Component vs Asset
![image](https://user-images.githubusercontent.com/99332618/197742097-049bce9d-756c-464d-98a0-5397ec2b6c68.png)

# Cleanup Policies & Scheduled Tasks
![image](https://user-images.githubusercontent.com/99332618/197742418-2841dca1-bdad-4ccb-996d-ae958edc7e7e.png)


