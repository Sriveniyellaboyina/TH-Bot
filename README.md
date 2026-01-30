# 🤖 TH-Bot (Technical Hub Chatbot)

TH-Bot is an intelligent chatbot designed for **Technical Hub** to provide instant assistance, event registration, and mentor/course guidance.  
It is built with **AWS cloud services** and supports integration with websites and applications to deploy.

**Why TH-Bot?**
- Reduces manual effort in answering repetitive queries  
- Provides real-time assistance for students  
- Easy integration with websites & apps  
- Scalable and secure with AWS services  

---

## 🚀 Features
- ✅ **Answer FAQs** about Technical Hub  
- ✅ **Event Registration** via chatbot  
- ✅ **Mentor & Course Info** retrieval  
- ✅ **Integration with Web & Mobile Apps**  
- ✅ **AWS-powered Backend APIs**  
- ✅ **Secure Authentication with IAM Roles**  

---

## 🏗️ Architecture
The project follows a **cloud-native architecture**:

- **Frontend**: React / HTML / CSS / JavaScript  
- **Backend**: Flask (Python) / AWS Lambda (Serverless)  
- **Database**: AWS DynamoDB / S3  
- **Hosting**: AWS EC2, S3 (Static Hosting)  
- **Authentication**: AWS IAM Roles & Policies  
- **APIs**: AWS API Gateway  

**High-Level Flow:**
1. User interacts with the chatbot (UI).  
2. Frontend sends query → Backend API (Flask / Lambda).  
3. Backend fetches data from **DynamoDB** / **S3**.  
4. Response is processed and sent back to the chatbot UI.  

---

## 🛠️ Tech Stack
- **Languages**: Python, JavaScript, HTML, CSS  
- **Frameworks**: React, Flask  
- **Cloud Services**: AWS EC2, S3, API Gateway, Lambda, DynamoDB, IAM  
- **Tools**: Git, GitHub, VS Code  
