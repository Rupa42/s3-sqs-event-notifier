# -s3-sqs-event-notifier
A project to configure event notifications from AWS S3 to SQS when a file is uploaded.
#  S3 to SQS Event Notifier

This project sets up an AWS S3 bucket that sends notifications to an Amazon SQS queue whenever a new file is uploaded. It demonstrates how to use AWS services for event-driven architectures.

---

##  What You Will Learn

- How to create an S3 bucket and SQS queue
- How to configure S3 event notifications to SQS
- How to apply IAM policies for permission control
- How to test file uploads and receive events
- How to automate using Terraform (coming soon)

---

##  Project Structure
 s3-sqs-event-notifier/
├── infra/ # Infrastructure as Code (Terraform)
├── src/ # Optional: Python script to read SQS messages
├── docs/ # Diagrams, notes, screenshots
├── .gitignore
└── README.md


---

##  Setup Instructions

### Prerequisites

- AWS account
- AWS CLI configured (`aws configure`)
- Terraform installed (optional)

### Steps

1. Create S3 bucket
2. Create SQS queue
3. Add IAM policy to allow S3 → SQS
4. Configure S3 event notification
5. Upload file to S3 and test

(These steps will be documented in detail as we implement them)

---

##  Glossary

| Term | Definition |
|------|------------|
| S3 | Amazon Simple Storage Service |
| SQS | Simple Queue Service |
| Event Notification | A message triggered by a change in a resource |
| IAM Policy | Permissions document that controls access |
| Terraform | Infrastructure as Code tool |

---

##  Status

 In Progress — Terraform setup is next

---

##  Screenshots

(– add screenshots of AWS console, file upload, SQS message)

---

##  Author

[Rupa Mishra](https://github.com/rupa42)

---


