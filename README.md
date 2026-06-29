# Automate AWS Resource Provisioning using Python (boto3)

## 📌 Project Overview

This project automates AWS resource provisioning using Python and the boto3 SDK. Instead of creating resources manually through the AWS Management Console, the project provisions AWS infrastructure programmatically.

## 🎯 Objective

- Automate AWS resource creation using Python scripts.
- Eliminate manual configuration through the AWS Console.
- Learn Infrastructure Automation with AWS SDK (boto3).

---

## 🛠️ AWS Services Used

- AWS IAM
- Amazon EC2
- Amazon S3
- AWS CLI
- boto3 (Python SDK)

---

## 💻 Technologies Used

- Python 3.x
- boto3
- AWS CLI
- Visual Studio Code
- Git
- GitHub

---

## 📂 Project Structure

```
aws-resource-provisioning-boto3/
│
├── create_iam.py
├── create_s3.py
├── create_ec2.py
├── list_resources.py
├── delete_resources.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Prerequisites

- AWS Account
- AWS CLI Installed
- Python 3.x
- boto3

Install boto3

```bash
pip install boto3
```

Configure AWS CLI

```bash
aws configure
```

Enter:

- AWS Access Key ID
- AWS Secret Access Key
- Region
- Output Format (json)

---

## 🚀 Features

- Create IAM User
- Create S3 Bucket
- Launch EC2 Instance
- List AWS Resources
- Delete Resources
- Fully Automated Infrastructure Provisioning

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/your-username/aws-resource-provisioning-boto3.git
```

Move into the project folder

```bash
cd aws-resource-provisioning-boto3
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the scripts

```bash
python create_iam.py
python create_s3.py
python create_ec2.py
```

To clean up resources

```bash
python delete_resources.py
```

---

## 📋 Expected Output

- IAM User created successfully
- S3 Bucket created successfully
- EC2 Instance launched successfully
- AWS resources listed successfully
- Resources deleted successfully (Cleanup)

---

## 📚 Learning Outcomes

- AWS SDK (boto3)
- Infrastructure Automation
- IAM Management
- EC2 Provisioning
- S3 Bucket Automation
- AWS CLI Configuration
- Python Scripting for Cloud

---

## 🔮 Future Enhancements

- Create VPC automatically
- Launch RDS Database
- Create Lambda Functions
- Add CloudWatch Monitoring
- Automate using CloudFormation
- Add Logging and Exception Handling

---

## 👩‍💻 Author

Neha Balkawade
