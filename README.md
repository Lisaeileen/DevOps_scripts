# DevOps Automation Scripts

##  Overview
This repository contains essential Bash scripts for automating common DevOps tasks. These scripts help with system setup, backup management, CI/CD deployment, Docker monitoring, and more. Perfect for streamlining operations, reducing manual work, and improving system reliability.

##  Scripts Included

### 1️ **System Setup Script** (setup_script.sh)
A script to set up a new server with essential tools like Docker, Kubernetes, and AWS CLI.
- Updates system packages
- Installs required software
- Configures SSH keys and user permissions

### 2️ **Git Auto-Commit & Push Script** (push_script.sh)
Automates Git commits and pushes with timestamped messages.
- Adds all modified files
- Commits with the current date/time
- Pushes changes to GitHub

### 3️ **Docker Container Health Check** (healthcheck_script.sh)
Monitors running Docker containers and detects unhealthy instances.
- Lists running containers
- Checks for unhealthy containers
- Sends alerts (extendable to Slack, email, etc.)

### 4️ **Backup & Restore Script** (backup_script.sh)
Automates file and database backups with optional S3 upload.
- Compresses and saves important directories

### 5️ **CI/CD Deployment Script** ([deploy_script.sh)
Deploys an application from GitHub to a remote server.
- Pulls the latest code from a Git repository
- Restarts the application service
- Can be integrated into a CI/CD pipeline

##  How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/lisaeileen/devOps_scripts.git
   cd devOps_scripts
   ```
2. Grant execution permissions to a script:
   ```sh
   chmod ugo+x (script-name)
   ```
3. Run the script:
   ```sh
   ./(script-name)
  

##  Contributing
Feel free to fork the repository and submit pull requests with improvements!

---
## Follow me on GitHub: [@lisaeileen] (https://github.com/lisaeileen)

