# Tahir Alakbarli

Computer Science student at Eotvos Lorand University in Budapest, focused on Cloud and DevOps engineering.

I build hands-on projects with AWS, Terraform, Linux, Docker, Kubernetes, GitHub Actions, and GitLab CI/CD. My recent work focuses on infrastructure as code, automated delivery pipelines, container orchestration, cloud security, and troubleshooting deployed systems.

I am currently looking for Cloud or DevOps internship opportunities where I can strengthen these skills in a professional environment.

## Certifications

- AWS Certified Solutions Architect - Associate
- AWS Certified Cloud Practitioner
- HashiCorp Certified: Terraform Associate
- GitLab Certified Associate - GitLab CI/CD

## Technologies

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab_CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

## Featured Projects

### [Integrated Infrastructure and Delivery](https://github.com/Tahir-Alakbarli/Integrated-Infrastructure-Delivery)

An end-to-end infrastructure and delivery project that connects Terraform, Amazon EKS, Amazon ECR, Docker, Kubernetes, and GitHub Actions.

Terraform provisions the AWS networking, IAM roles, ECR repository, and EKS infrastructure. GitHub Actions tests the application, builds a Docker image, pushes it to ECR, and deploys the selected image version to Kubernetes. GitHub authenticates to AWS through OIDC instead of permanent access keys.

**Main technologies:** Terraform, AWS, EKS, ECR, Kubernetes, Docker, GitHub Actions, IAM, OIDC

### [Kubernetes Deployment and Recovery](https://github.com/Tahir-Alakbarli/Kubernetes-Project)

A local Kubernetes project built with kind and the System Health API.

The project demonstrates Deployments, Services, replicas, health probes, resource limits, rolling updates, rollout history, rollback, scaling, and automatic Pod replacement. Failure and recovery were tested by manually deleting Pods and confirming that Kubernetes restored the required state.

**Main technologies:** Kubernetes, kind, Docker, Linux, kubectl, YAML

### [Website Uptime Monitoring](https://github.com/Tahir-Alakbarli/Website-Uptime-Monitoring)

A containerized Flask and MySQL application that checks website availability, HTTP responses, response times, failures, and recent check history.

GitLab CI/CD tests and builds the application before deploying it to AWS. Terraform manages the supporting AWS infrastructure, while Docker Compose runs the monitoring application, test website, and MySQL database.

**Main technologies:** GitLab CI/CD, Terraform, AWS, Docker, Flask, Python, MySQL, Linux

### [Terraform AWS Web Infrastructure](https://github.com/Tahir-Alakbarli/Terraform-AWS-Web-Infrastructure)

A complete AWS web infrastructure created through Terraform.

The project provisions a VPC, public subnets in multiple Availability Zones, routing, security groups, an Application Load Balancer, a target group, a Launch Template, and an Auto Scaling Group. EC2 instances configure and serve the website automatically through user data.

**Main technologies:** Terraform, AWS, VPC, EC2, ALB, Auto Scaling, IAM, Linux

### [System Health API](https://github.com/Tahir-Alakbarli/System-Health-API)

A small containerized Python API used to demonstrate automated testing and delivery with GitHub Actions.

The workflows test the application, build its Docker image, and handle deployment operations. The project also included a self-hosted GitHub Actions runner on Amazon EC2.

**Main technologies:** GitHub Actions, Docker, Python, Flask, AWS EC2, Linux

## Other AWS Work

My earlier projects include:

- Static website delivery with Amazon S3 and CloudFront
- Serverless image uploads with AWS Lambda and S3
- Private MySQL database deployment with Amazon RDS
- Highly available web infrastructure with EC2, ALB, and Auto Scaling
- Dockerized Flask application deployed to EC2 with Nginx

## Contact

- Location: Budapest, Hungary
- GitHub: [Tahir-Alakbarli](https://github.com/Tahir-Alakbarli)
- LinkedIn: Tahir Alakbarli
- Open to Cloud and DevOps internship opportunities
