# WhatsApp Automation with n8n & WhatsApp Business Cloud API  

## 📌 Overview  
This project demonstrates how to automate WhatsApp communication using **n8n Cloud** and the **WhatsApp Business Cloud API**.  
The automation workflow is designed to:  
- Capture incoming WhatsApp messages.  
- Process the input with an **AI-powered model** for dynamic replies.  
- Send back personalized responses using **message templates** with variables.  
- Deliver **media-rich messages** (images, banners, structured content).  

An example use case implemented here is the **Tech Updates Group invitation**, where users receive a personalized message and image directly on WhatsApp.  

---

## ⚙️ Workflow Components  

### 1. WhatsApp Chatbot Automation  
- **WhatsApp Trigger** → Captures incoming messages.  
- **Message a Model** → AI analyzes the input and generates a response.  
- **Send Message** → Sends the AI response back to the user.  

### 2. Template Automation  
- **Manual Trigger (Execute Workflow)** → Starts the template workflow.  
- **Send Template** → Delivers predefined WhatsApp templates with variables (e.g., user name, group details, image).  

---

## 🚀 Features  
- ✅ **AI-Powered Replies** – Dynamic responses based on incoming user messages.  
- ✅ **Personalized Templates** – Customizable with variables like name and content.  
- ✅ **Media Support** – Send images, banners, and structured messages.  
- ✅ **Automation Ready** – Works for onboarding, campaigns, notifications, and engagement.  

---

## 🛠️ Tools & Technologies  
- **n8n Cloud** (workflow automation)  
- **WhatsApp Business Cloud API**  
- **Custom WhatsApp Message Templates**  
- **AI Model Integration**  

---

## 📖 Example Use Case  
### Tech Updates Group Invitation  
When a user interacts, they automatically receive:  
- A **personalized greeting** (`Hi {{UserName}}`)  
- A **banner image** (Tech Updates cover)  
- A **welcome message** with group details  
- A **CTA button** (Yes, I want to Join)  

---

## 🔮 Future Enhancements  
- Adding analytics to track user interactions.  
- Expanding AI response capabilities.  
- Integration with CRMs for customer data management.  

---


## 📌 Author  
👤 Mohammed Rifaiz  
