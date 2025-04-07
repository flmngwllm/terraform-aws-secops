# AWS Security Automation

Automated compliance monitoring and remediation for AWS using Terraform, AWS Config, and Security Hub.

![Architecture Diagram](docs/architecture.png)

## Features

- **Continuous Compliance**: 20+ pre-configured AWS Config rules
- **Auto-Remediation**: Lambda functions fix violations in real-time
- **Cost-Optimized**: Scheduled shutdowns and spot instances
- **Alerting**: Slack/email notifications for critical findings

## Built With
- **Terraform**: Infrastructure as Code
- **Python**: Lambda remediation scripts
- **AWS Config**: Compliance tracking
- **GitHub Actions**: CI/CD pipelines
