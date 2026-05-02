# 🚀 AI Blog Generator from YouTube Videos (Fully Automated System)

An end-to-end AI automation system that converts YouTube videos into **SEO-optimized blog posts**, generates **AI images**, and sends the final output via email — all using workflow automation.

---

## 🧠 Project Overview

This project automates the entire content creation pipeline:

- Extracts transcript from YouTube videos  
- Uses AI to generate structured SEO blog posts  
- Creates blog images using AI  
- Formats output and sends it via Gmail  

This system eliminates manual blogging and enables **1-click content repurposing from videos**.

---

## ⚙️ Tech Stack

- :contentReference[oaicite:0]{index=0} – Workflow automation engine  
- :contentReference[oaicite:1]{index=1} Gemini API – Blog generation & structuring  
- :contentReference[oaicite:2]{index=2} – AI image generation  
- Supadata API – YouTube transcript extraction  
- Gmail API – Email automation  

---

## 🔥 Features

- 🎥 YouTube video → transcript extraction  
- 🤖 AI-powered SEO blog generation  
- 🧠 Automatic title, description, and keyword creation  
- 🖼️ AI-generated blog images  
- 📧 Automated email delivery of blog content  
- ⚡ Fully no-code / low-code automation pipeline  

---

## 🏗️ System Architecture
```
YouTube Video
↓
Supadata API (Transcript Extraction)
↓
Gemini AI (Blog + SEO + Image Prompt)
↓
Stability AI (Image Generation)
↓
n8n Workflow Processing
↓
Gmail (Final Output Delivery)
```

---

## 📁 Project Structure
```
ai-blog-generator-n8n/
│
├── README.md
├── workflow.json
│
├── screenshots/
│ ├── workflow.png
│ ├── email-output.png
│ ├── generated-image.png
│
```

---

## 📦 How to Use

### 1. Import Workflow
- Open n8n
- Import `workflow.json`

### 2. Configure APIs
Set your API keys for:
- Gemini AI
- Stability AI
- Supadata
- Gmail API

### 3. Run Workflow
- Trigger workflow manually or via webhook
- Paste YouTube video URL
- Get AI-generated blog + image + email output

---

## 📸 Output Example

- SEO blog article generated from video  
- AI-generated featured image  
- Email with formatted HTML blog content  

---

## 🧠 Challenges Solved

- Handled API quota limitations for image generation  
- Converted Base64 AI image output into binary format for email attachments  
- Designed modular AI pipeline for scalable automation  
- Ensured SEO-optimized blog structure using prompt engineering  

---

## 🚀 Future Improvements

- Add WordPress auto-publishing  
- Add blog image hosting (CDN)  
- Add multi-language blog generation  
- Convert into SaaS product  

---

## 💡 Use Cases

- Content creators  
- Bloggers  
- Digital marketers  
- SEO agencies  
- YouTube automation channels  

---

## ⭐ About This Project

This project demonstrates real-world **AI automation, workflow engineering, and content generation systems**.  
It can be extended into a full SaaS product for automated content marketing.

---

## 👨‍💻 Author

Sagor Das  
Computer Science & Engineering Student  
Interest: AI, Automation, Web Development
