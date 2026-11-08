<div align="center">

# Namaste 🙏, I am Pratham L Gaikwad

### Full Stack Developer & DevOps Enthusiast

<a href="https://github.com/pratham-12-lab">
<img src="https://img.shields.io/badge/GITHUB-CONNECT-blue?style=for-the-badge&logo=github"/>
</a>
<a href="https://linkedin.com/in/pratham-l-gaikwad">
<img src="https://img.shields.io/badge/LINKEDIN-CONNECT-blue?style=for-the-badge&logo=linkedin"/>
</a>

<br/>
<br/>

<img src="https://komarev.com/ghpvc/?username=pratham-12-lab&style=for-the-badge"/>

</div>


---

<div align="center">

### "Success is achieved through effort, not by mere wishes."

</div>


---


# Professional Summary

- **Full Stack Developer** | MERN Stack Development
- **IoT Engineer** | Cloud Connected Hardware Systems
- **DevOps Enthusiast** | AWS, Docker, Jenkins, Linux
- **Machine Learning Explorer** | AI & ML Technologies


---


# The Engineering Architect

I am a Computer Science Engineer with a systems-first mindset, focused on building scalable applications, IoT platforms, and automated cloud solutions.

- **Full Stack Engineering:** Building scalable web applications using React, Node.js, Express.js and databases.
- **IoT System Design:** Developing cloud-connected hardware solutions with real-time monitoring.
- **Cloud & DevOps:** Working with AWS services, Docker containers, CI/CD pipelines and deployment automation.


---


# Engineering Projects


## 🛡️ CrimeLens — Intelligent Cybercrime Analysis & Complaint Drafting System

[Live Demo](https://cyber-lens-pi.vercel.app/)

🏆 **Project Expo Winner Out of 60 Teams**

CrimeLens is an integrated, dual-platform cybersecurity ecosystem designed to protect Indian citizens from the rising tide of digital financial fraud, such as UPI scams, phishing, and fake online job offers. It provides a comprehensive solution covering both proactive threat prevention and reactive incident management to bridge the gap between technical vulnerability and accessible legal recourse.

### Platform Ecosystem

- **The Web Application (Reactive AI Layer):** An intelligent portal that helps victims automatically draft formal, legally mapped police complaints. It features a sophisticated NLP pipeline that accepts incident narratives in English, Hindi, or Kannada. Without relying on labeled training data, it translates regional inputs, classifies the fraud into one of eight categories using zero-shot inference, extracts forensic entities (like UPI IDs and transaction amounts), and maps the offense to specific provisions of the Bharatiya Nyaya Sanhita (BNS), 2023, and the IT Act, 2000. It generates a downloadable, structured PDF complaint and an evidence-preservation checklist.
- **The Mobile Application (Proactive Rule-Based Layer):** A standalone Android application operating as a continuous foreground service. It acts as an active defense shield, utilizing native Java broadcast receivers to intercept incoming SMS and call events in real-time. It analyzes these communications offline against a heuristic engine of over 500 threat patterns in under 5 milliseconds, triggering immediate, high-priority notifications to warn users before they interact with malicious phishing links or social engineering attempts.

### Technical Stack & Architecture

- **Web Client (Frontend):** React 18, Vite, Tailwind CSS, React Router v6, Axios
- **Mobile Client (Frontend & Native):** React Native 0.74 (Bare Workflow), Native Android Java (SmsReceiver, Call Modules, BroadcastReceiver, Foreground Services), @notifee/react-native
- **Backend & APIs:** Node.js, Express.js, PDFKit
- **AI & NLP Pipeline:** BART-MNLI (Zero-Shot Classification), NLLB-200 (Multilingual Translation), Custom Regex-based Named Entity Recognition (NER)
- **Database, Storage & Security:** MongoDB Atlas (Mongoose ODM), JWT Auth (localStorage/AsyncStorage), bcrypt (Password Hashing)


---


## 🖨️ PrintBridge — Cloud-to-Edge Remote Printing System (PaaS)

[Live Demo](https://printbridge-by-vps.onrender.com/) 

**Role:** IoT Engineer & Full-Stack Developer  
**Team:** Team VPS (4 Members)  
**May 2026**

🏆 **2nd Runner-Up — IoT Project Expo 2026 (IIC, AICTE)**

### System Performance & Reliability
- Reduced end-to-end remote print latency to under 30 seconds by architecting a Node.js/Express cloud backend that dispatches jobs through an automated queue to a local edge daemon in real time.
- Designed a fault-tolerant edge agent with multi-OS driver fallbacks, mutex locks to eliminate race conditions on shared hardware, and exponential-backoff retries for resilience under concurrent load.
- Eliminated server out-of-memory crashes with a stream-based rendering pipeline and zero-retention file lifecycle; instrumented real-time health monitoring via ThingSpeak telemetry.

### Hybrid IoT Architecture
Designed a three-layer architecture spanning cloud (**Node.js, Cloudinary, Razorpay, ThingSpeak**), edge (**Arduino UNO R4 WiFi HTTPS polling**), and local (**Node.js Printer Agent using Serial UART 115200 baud**) with exactly-once job processing.

### Hardware State Machine
Built an IR sensor-based printer monitoring pipeline with RGB LED states:

🟢 Idle  
🔵 Printing  
🟡 Collect Pages  
🔴 Error

Integrated buzzer alerts and tray detection to prevent document mixing.

### Real-Time Analytics & Payments
Integrated ThingSpeak dashboards for:
- Revenue tracking
- Queue monitoring
- Printer status
- Colour ratio analytics

Implemented Razorpay server-side verification before print execution.

### Tech Stack
- Node.js, Express, Sharp, PDFKit, ThingSpeak


---


## 💼 Job Portal — Complete Full-Stack Solution

[Live Demo](https://job-portal-frontend-2du2.onrender.com/) 

**Role:** Full-Stack Developer  

A comprehensive, enterprise-grade platform that revolutionizes the job search and recruitment process, connecting talented professionals with their dream careers.

### Core Features
- **Smart Job Matching:** Implemented advanced job search filters based on skills, location, and experience.
- **Application Management:** Integrated secure resume upload functionality (via Cloudinary) and robust backend APIs for seamless application tracking.
- **Responsive UI:** Designed an accessible, mobile-first interface using **React** and **Tailwind CSS**, ensuring a seamless experience across all devices.
- **Real-Time Communication:** Powered by Socket.io for instant notifications and direct chat between candidates and recruiters.

### Tech Stack & Architecture
- **Frontend:** React, Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **Security & Cloud:** JWT Authentication, Role-Based Access Control (RBAC), Cloudinary (File Storage)
- **Deployment:** Render & MongoDB Atlas


---


# Languages & Tools


## Frontend Development

<p>
<img src="https://skillicons.dev/icons?i=html,css,js,react,bootstrap,tailwind"/>
</p>


## Backend Development

<p>
<img src="https://skillicons.dev/icons?i=nodejs,express,java,spring"/>
</p>


## Database

<p>
<img src="https://skillicons.dev/icons?i=mongodb,mysql"/>
</p>


## DevOps & Cloud

<p>
<img src="https://skillicons.dev/icons?i=aws,docker,jenkins,linux"/>
</p>


## Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,cpp"/>
</p>




<div align="center">

### Building scalable solutions by combining  
### Software ⚡ Cloud ☁️ IoT 🌐

</div>
