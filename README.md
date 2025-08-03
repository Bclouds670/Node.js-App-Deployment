# Node.js App Deployment

## Steps to Clone and Run
- git clone <REPO_URL>
- npm install
- npm start

## Jenkins Setup
- Installed Jenkins on Ubuntu 20.04.
- Created pipeline to build, test, and deploy.

## Security
- Enabled matrix-based security in Jenkins.
- Created roles: admin, developer.
- Restricted anonymous access.

## Deployment
- Configured NGINX reverse proxy.
- Used DuckDNS for DNS.
- Installed SSL via Let's Encrypt.

## Monitoring
- Configured AWS CloudWatch for monitoring the Linux server and Node.js application.
- CloudWatch captures system metrics such as CPU, memory, disk usage, and process health.
- Set up CloudWatch Agent on the server for custom metric collection and log forwarding.

## Scripts
- deploy.sh: deploys application

