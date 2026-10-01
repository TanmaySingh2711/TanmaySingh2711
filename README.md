<div align="center">

# Hi, I'm Tanmay Singh 👋

**Final-year B.E. (AI & Data Science) student · Aspiring AI Engineer**

📍 Bengaluru, Karnataka, India

<a href="https://linkedin.com/in/tanmay-singh-216380334/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:tanmaysingh8970@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://tanmayportfolio-five.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<br/>
<a href="https://leetcode.com/u/vcYjoLhKrp/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
<a href="https://www.geeksforgeeks.org/profile/tanmaysiaq6p"><img src="https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="GeeksforGeeks"/></a>
<a href="https://www.hackerrank.com/profile/tanmaysingh4628"><img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black" alt="HackerRank"/></a>

</div>

---

## 💫 About Me

I'm a final-year B.E. student in **Artificial Intelligence and Data Science** who builds AI software that solves practical problems.

- 🧠 Skilled in **Python, machine learning, deep learning, computer vision** and **web development**
- 🛠️ Built a gesture-controlled game, a self-learning game-testing agent and an AI shopping assistant with secure test payments
- 🎯 Currently seeking an **entry-level AI Engineer** role

---

## 🚀 Featured Projects

### 🖐️ [CNN-Based Gesture Controlled Pac-Man](https://github.com/TanmaySingh2711/gesture-controlled-game)

A Pac-Man-style maze game you steer with hand gestures in front of a webcam.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-2E7D32?style=flat-square)

- Fine-tuned a **MobileNetV2 CNN** on a 2,000-image HaGRID subset to classify 4 gestures (fist, palm, thumbs up, thumbs down) into left, right, up and down
- **99.0% test accuracy** on held-out images and **99.6%** on 2,000 images of 1,727 people the model had never seen
- Real-time pipeline with a 0.90 confidence threshold and 3-of-5 frame temporal smoothing to prevent wrong turns
- Game runs at **~60 FPS** while gesture recognition runs at **30 FPS** on a separate thread
- About **510 automated tests**, 94% coverage, CI on Windows, macOS and Linux

### 🎮 [Glitch Hunter: AI Game Testing System](https://github.com/TanmaySingh2711/glitch_hunter_project)

A reinforcement learning agent that plays a Mario-style Pygame game on its own to find bugs.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-555555?style=flat-square)
![Gymnasium](https://img.shields.io/badge/Gymnasium-555555?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

- Trained a **PPO agent** in two stages for **16M steps** across **8 parallel environments**
- Explored **84.25%** of the level's reachable pixels while still finishing the level in **56.6%** of 500 test episodes (vs 46.8% for the starting model)
- Runtime glitch detector checks game-state rules for abnormal movement, clipping, score and coin bugs
- Saves screenshot, GIF and PDF report evidence for every bug it finds
- Live **Flask + Socket.IO dashboard** streams gameplay, actions, rewards and detected glitches

### 🛒 [Razorpay Agentic Commerce](https://github.com/TanmaySingh2711/razorpay-agentic-commerce) · [Live Demo](https://razorpay-agentic-commerce-xi.vercel.app)

An AI shopping assistant where the AI only suggests a product and the server decides everything about money.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white)

- **Google Gemini** buyer agent understands plain-language shopping requests and proposes a product within the user's budget
- Server validates price, spending limits, inventory and authorization; purchases above ₹3,000 need human approval
- **Razorpay Test Mode** integration with signature and webhook verification, payment retries and inventory reservation
- Every decision and state change is stored in an audit trail
- Deployed on **Vercel**

### 🌐 [Portfolio Website](https://github.com/TanmaySingh2711/tanmay_portfolio) · [Live Site](https://tanmayportfolio-five.vercel.app/)

My personal portfolio, built with Next.js, React, TypeScript, Tailwind CSS and Framer Motion, deployed on Vercel.

---

## 💻 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)

**AI & ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-555555?style=flat-square)
![Gymnasium](https://img.shields.io/badge/Gymnasium-555555?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Google Gemini API](https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Frameworks & Libraries**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-2E7D32?style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**APIs & Databases**

![REST APIs](https://img.shields.io/badge/REST_APIs-555555?style=flat-square)
![Razorpay API](https://img.shields.io/badge/Razorpay_API-0C2451?style=flat-square&logo=razorpay&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Developer Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

---

## 🏆 Hackathons

- **Hire-4-Thon**, National Level Hackathon (2026) · [View Certificate](https://tanmayportfolio-five.vercel.app/certificates/hire-4-thon-national-hackathon.pdf)
- **Hackathon-24**, College Level Hackathon (2024) · [View Certificate](https://tanmayportfolio-five.vercel.app/certificates/hackathon-24-kssem.pdf)

---

## 📜 Certifications

- **Introduction to Machine Learning**, VOIS (2025) · [View Certificate](https://tanmayportfolio-five.vercel.app/certificates/introduction-to-machine-learning-vois.pdf)
- **Getting Started with Artificial Intelligence**, IBM SkillsBuild (2024) · [View Certificate](https://tanmayportfolio-five.vercel.app/certificates/getting-started-with-ai-ibm.pdf)
- **Generative AI Literacy**, IT-ITeS SSC / FutureSkills Prime (2025) · [View Certificate](https://tanmayportfolio-five.vercel.app/certificates/generative-ai-literacy-futureskills.pdf)
