# 🚀 Node.js App Deployment

## 📝 Steps to Clone and Run

### 🎯 Goal
➤ Get the source code locally and run the Node.js app for quick testing and development.

- 🔹 `git clone <REPO_URL>`
- 🔹 `npm install`
- 🔹 `npm start`

## 🛠 Jenkins Setup (Freestyle Project)

### 🎯 Goal
➤ Automate build, test, and deployment using Jenkins Freestyle Projects for easy configuration.

- 🔹 Installed Jenkins on Ubuntu 20.04.
- 🔹 Created Freestyle project to build, test, and deploy the application.
- 🔹 Configured build steps and post-build actions as needed.

## 🔐 Security

### 🎯 Goal
➤ Secure Jenkins by enabling matrix-based security and defining user roles.

- 🔹 Enabled matrix-based security in Jenkins.
- 🔹 Created roles: admin, developer.
- 🔹 Restricted anonymous access.

## 🚧 Deployment

### 🎯 Goal
➤ Serve the app securely using NGINX reverse proxy, dynamic DNS, and SSL encryption.

- 🔹 Configured NGINX reverse proxy.
- 🔹 Used DuckDNS for DNS.
- 🔹 Installed SSL via Let's Encrypt.

## 📊 Monitoring

### 🎯 Goal
➤ Monitor server and app health proactively using AWS CloudWatch.

- 🔹 Configured AWS CloudWatch for Linux server and Node.js app.
- 🔹 Captures CPU, memory, disk usage, and process health.
- 🔹 Set up CloudWatch Agent for custom metrics and log forwarding.

## ⚙️ Scripts

### 🎯 Goal
➤ Automate deployment with a reusable shell script.

- 🔹 `deploy.sh`: deploys the application
