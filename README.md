# 📬 Infoscribe

**AI-Powered Personalized Newsletter Platform**

Infoscribe is a solo-built AI newsletter platform that curates, summarizes, and delivers news based on user interests — cleanly and automatically.  
It’s designed to solve the problem of *information overload* by leveraging **LangChain**, **AWS automation**, and a clean **Next.js** frontend.

Created by [Heejoon Yi](https://www.linkedin.com/in/heejoon-yi/), Computer Science & TSM major at Stony Brook University.  
Currently in active **beta** → [https://infoscribe.me](https://infoscribe.me)

---

## ✨ What It Does

- 💡 **Curates content** based on user-selected keywords and categories  
- 🧠 **Summarizes articles** using LangChain + OpenAI  
- 🕓 **Automates scheduling** with AWS Lambda & EventBridge  
- ✉️ **Delivers newsletters** via SES, stored in S3  
- 📱 **Mobile-first UX** with modern design and Zustand state management

---

## 🧱 System Overview

```
User → Next.js Frontend
     → Express API (Docker, EC2)
         → Lambda → LangChain summarization
         → S3 (Newsletter Storage)
         → SES (Email Delivery)
         → RDS (MySQL Content DB)
```

---

## 🧪 Current Status

- ✅ MVP completed  
- 🧪 Beta testing with early users ongoing  
- 🗓️ Official launch planned for **May 2025**

---

## 🛤 Roadmap

- 🎙️ AI-generated podcast newsletters  
- 🧠 Smart content recommendations  
- 📈 Newsletter performance analytics  
- 🤝 Collaborative tools for creators  

---

## 🤝 Looking for Collaborators

Infoscribe is not fully open source — but I'm **actively seeking collaborators** for:

- AI/Backend development  
- Product/UX feedback  
- Launch/marketing support  
- Vision-aligned co-builders 🤝  

If this project resonates with you, let’s talk!  
📩 [Contact me on LinkedIn](https://www.linkedin.com/in/heejoon-yi/)
