# DevOps-Observability-Project
python flask with observability
🚀 Overview

This project provisions an AWS EC2 instance using Terraform and deploys:

Python Flask App
Prometheus
Grafana
Node Exporter

🏗 Architecture

Flask App → Node Exporter → Prometheus → Grafana

⚙️ Setup Instructions
1. Clone Repo
git clone https://github.com/YOUR_USERNAME/devops-observability-project.git

2. Configure Terraform
Update:
 key_name
 region

3. Deploy Infra
 terraform init
 terraform apply

4. Access Services
  Service	URL
  Flask App	http://EC2-IP:5000
  Prometheus	http://EC2-IP:9090
  Grafana	http://EC2-IP:3000

📊 Dashboards

Import dashboard ID: 1860

📦 Tech Stack
AWS EC2
Terraform
Docker
Prometheus
Grafana


🧹 Cleanup
terraform destroy
