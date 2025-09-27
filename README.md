# CoMate App – Your Intelligent To-Do List Companion

> 🏆 **CoMate App was built for the “Accelerate with LLaMA” Hackathon by Hacktiv8 x Meta.**

CoMate App is an intelligent To-Do list application designed to help users manage daily tasks more efficiently.
Beyond standard CRUD functionalities, it offers **AI-powered premium features** such as smart task prioritization and an integrated chatbot.

---

## 🎯 Target Audience

Students, professionals, freelancers, and busy individuals who want to manage tasks more efficiently with AI-powered recommendations and calendar integration.

---

## ❗ Problem Statement & Context

Many people struggle to manage daily tasks effectively, leading to missed deadlines, stress, and reduced productivity, which highlights the need for an intelligent task management solution.

---

## 💡 Solution Overview

CoMate App solves this by combining a smart to-do list with AI-powered prioritization, Google Calendar integration, and a built-in chatbot to keep users organized, focused, and productive.

---

## 🚀 Expected Impact & Future Plan

We aim to reduce stress, improve productivity, and help users make smarter decisions. Next steps include enhancing personalization, adding more integrations, and scaling CoMate App into a widely adopted productivity assistant.

---

## 🤖 How Do We Use LLaMA?

We use LLaMA via Groq API to power CoMate App’s chatbot and smart task prioritization, enabling fast, context-aware recommendations and natural conversations that bring intelligence to the to-do list experience.

---

## ⚙️ Technical Integration (Prompt + System)

We integrated LLaMA through Groq API calls orchestrated by **n8n**. The backend forwards user prompts to n8n, which formats and sends them to LLaMA, then returns the AI-generated response back to the frontend in real time.

---

## ✨ Key Features & User Journey

* Smart task management (create, edit, organize, track to-dos)
* Google Calendar integration for scheduling
* AI-powered task prioritization
* Interactive chatbot for assistance
  **User Journey:** Create tasks → receive AI recommendations → sync to calendar → stay supported via chatbot.

---

## 🏗️ Tech Stack

The tech stack is **MERN** (MongoDB, Express.js, React, Node.js) with **LLaMA 3 via Groq API** for AI, **n8n on Azure Container Apps** for orchestration, and both frontend & backend deployed on **Vercel**.

---

## 💰 Business / Monetization Model

CoMate App delivers value by boosting productivity and improving user experience with AI features, while generating revenue through a **premium subscription model** with unlimited tasks and advanced AI features.

---

## 📊 Business Model Canvas

| **Building Block**         | **Details**                                                                    |
| -------------------------- | ------------------------------------------------------------------------------ |
| **Revenue Streams**        | - Premium subscription <br> - Voucher-based plans                              |
| **Key Partnerships**       | - Groq API <br> - n8n <br> - Vercel <br> - Azure                               |
| **Key Activities**         | - App development <br> - AI integration <br> - User support                    |
| **Value Propositions**     | - AI task prioritization <br> - Calendar integration <br> - Productivity boost |
| **Customer Segments**      | - Students <br> - Professionals <br> - Freelancers <br> - Busy individuals     |
| **Key Resources**          | - MERN stack <br> - LLaMA 3 <br> - Cloud infrastructure                        |
| **Channels**               | - Web app on Vercel <br> - Social media promotion                              |
| **Cost Structure**         | - Hosting <br> - AI API usage <br> - Development <br> - Marketing              |
| **Customer Relationships** | - Self-service <br> - In-app AI chatbot support                                |

---

## 🔒 Ethics & Risk Mitigation

CoMate App addresses ethics and risks by:

* Ensuring **privacy** with JWT-secured authentication and minimal data storage
* Reducing **bias** through monitored prompts and responsible LLaMA usage
* Preventing **misuse** by limiting AI output strictly to productivity-related recommendations

---

## 👥 Developer

* **Bagus Angkasawan Sumantri Putra** — Team Leader
* **Ryan Nugroho** — Team Member

---
