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

## 📬 Contact
- **Email:** [franciscoanthony82@gmail.com](mailto:franciscoanthony82@gmail.com)
- **GitHub:** [AnthonyFrancisco21](https://github.com/AnthonyFrancisco21)
