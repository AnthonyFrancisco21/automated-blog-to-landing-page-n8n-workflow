# Automated Blog-to-Landing Page Workflow (n8n)

This project automates the process of creating a complete landing page from a simple topic input using AI and automation tools.
Built with n8n, this workflow fetches trending blog topics, enhances them with AI, generates a landing page with visuals, and emails the result to the user.

## 🚀 Features
 - 📬 Form Submission Trigger – Starts when a user enters their email and selects an interest topic.
 - 🔍 SerpApi Integration – Fetches trending news or blog topics related to the user’s chosen interest.
 - 🧩 Google Gemini API – Expands headlines into a full blog (title, introduction, body, conclusion).
 - 💻 AI HTML Generator – Creates a responsive, single-page landing page layout using HTML, CSS, and JS.
 - 🖼️ Hugging Face Model – Generates a realistic blog image based on the topic.
 - 📎 Gmail Node – Sends the final HTML and PNG files to the user’s email.


## ⚙️ Workflow Overview

 - Form Trigger: User submits email + topic.
 - SerpApi: Fetches trending blog headlines.
 - Gemini AI: Expands one headline into structured blog content.
 - Gemini AI (HTML): Generates landing page HTML code.
 - Hugging Face API: Creates a visual image for the blog.
 - Merge + Email: Combines image + HTML and sends them as attachments via Gmail.

## 🔐 API Keys (Important)

⚠️ Before using this workflow:
Replace the placeholder API keys with your own credentials inside n8n:
```
YOUR_HUGGINGFACE_API_KEY
YOUR_SERPAPI_KEY
```
These keys were removed from this public version for security.

## 🧩 Workflow Overview
<img width="1619" height="614" alt="image" src="https://github.com/user-attachments/assets/8defcf9e-77b1-4261-9d74-9328ab334b15" />

## 💻 Generated HTML Output  
Preview of the AI-generated landing page built using HTML, CSS, and JavaScript.
<img width="600" alt="image" src="https://github.com/user-attachments/assets/7fa8d28f-6b46-4070-bea0-2d53f3b805b6" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/61b3e15c-f76f-45b5-ad81-56b822682821" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/75771c9d-8e18-4d16-93a0-8879ad2f2a62" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/bdfd2c0b-77fe-42a0-9c49-03ae25300949" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/c2075d81-22de-4734-84b7-3555e6b7fcce" />

## 📬 Contact
- **Email:** [franciscoanthony82@gmail.com](mailto:franciscoanthony82@gmail.com)
- **GitHub:** [AnthonyFrancisco21](https://github.com/AnthonyFrancisco21)
