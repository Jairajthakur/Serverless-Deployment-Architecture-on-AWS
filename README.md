# Serverless Deployment Architecture on AWS
This project demonstrates a fully automated and serverless website deployment architecture using AWS services like CodePipeline, CodeBuild, CodeDeploy, CloudFront, WAF, ACM, and S3.

## Architecture Overview
- **S3** – Hosts the static website.
- **CloudFront** – Distributes content globally with low latency.
- **ACM** – Manages SSL/TLS certificates for HTTPS.
- **WAF** – Protects against common web exploits.
- **CodePipeline** – Automates CI/CD workflow.
- **CodeBuild** – Builds and tests code.
- **CodeDeploy** – Manages deployment to S3/CloudFront.

## Deployment Flow
1. Code is pushed to GitHub.
2. AWS CodePipeline triggers automatically.
3. CodeBuild builds and validates artifacts.
4. CodeDeploy uploads the build to S3.
5. CloudFront cache invalidation ensures live updates.

## Tech Stack
AWS | CI/CD | CloudFront | Serverless | Secure Deployment

## 👨‍💻 Author

📧 Email: th.jairaj@gmail.com</br>
🌐 GitHub: https://github.com/Jairajthakur</br>
💼 LinkedIn: https://linkedin.com/in/jairajsinghchauhan</br>
