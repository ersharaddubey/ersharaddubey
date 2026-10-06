<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0F2A2B&height=190&section=header&text=Sharad%20Dubey&fontColor=E6F1EF&fontSize=60&fontAlignY=40&desc=Senior%20Full%20Stack%20Developer&descColor=5FD3B0&descSize=22&descAlignY=62" alt="Sharad Dubey – Senior Full Stack Developer" width="100%"/>

**Building secure, real-time MERN applications for healthcare and AI products.**

10+ years of shipping web applications. I own the full path: architecture, database design, APIs, real-time features and AWS deployment, with a focus on protecting sensitive data.

<a href="mailto:ersharaddubey@gmail.com"><img src="https://img.shields.io/badge/Email_me-5FD3B0?style=for-the-badge&logo=gmail&logoColor=0F2A2B" alt="Email"/></a>
<a href="#-mern-stack-projects"><img src="https://img.shields.io/badge/See_projects-0F2A2B?style=for-the-badge&logoColor=5FD3B0&labelColor=0F2A2B&color=0F2A2B&label=%E2%86%93" alt="Projects"/></a>
<a href="tel:+918922096699"><img src="https://img.shields.io/badge/%2B91--8922096699-1F4FD8?style=for-the-badge&logo=googlemessages&logoColor=white" alt="Phone"/></a>

<br/>

![MongoDB](https://img.shields.io/badge/M-MongoDB-0F2A2B?style=flat-square&logo=mongodb&logoColor=5FD3B0)
![Express](https://img.shields.io/badge/E-Express.js-0F2A2B?style=flat-square&logo=express&logoColor=5FD3B0)
![React](https://img.shields.io/badge/R-React.js-0F2A2B?style=flat-square&logo=react&logoColor=5FD3B0)
![Node](https://img.shields.io/badge/N-Node.js-0F2A2B?style=flat-square&logo=nodedotjs&logoColor=5FD3B0)

</div>

---

## 📊 At a glance

<div align="center">

| **10+** | **10** | **50%** | **40%** |
|:---:|:---:|:---:|:---:|
| years building software | developers mentored and managed | faster document processing | faster UI interactions |

</div>

---

## 🧱 The MERN stack

| | Technology | What I do with it |
|:---:|---|---|
| **M** | **MongoDB** | Schemas, encrypted fields, audit data |
| **E** | **Express.js** | REST APIs, validation, RBAC |
| **R** | **React.js** | Role-aware dashboards and portals |
| **N** | **Node.js** | Services, Socket.IO, AWS deploys |

---

## 🚀 MERN stack projects

Full-stack systems where I handled design, schema, APIs and deployment. Expand **Architecture** on any project to see how it is layered.

### 🏥 MedSecure
`Healthcare`

**HIPAA-compliant healthcare management system**
<sub>React.js · Node.js · Express.js · MongoDB · JWT · AWS</sub>

- Patient records, appointments, prescriptions and clinical workflows in one platform.
- PHI protected by encryption at rest and in transit, with an audit log of every access, change and export.
- Role-based access for doctors, nurses, admin, reception and patients, plus consent checks before PHI is shared.

<details>
<summary><b>Architecture</b></summary>

| Layer | Details |
|---|---|
| **Presentation** | React.js patient and provider portals |
| **Auth** | JWT, RBAC, session hardening |
| **Business logic** | Patient, EMR, Appointment, Billing modules |
| **Compliance** | PHI encryption, access logs, consent checks |
| **Data** | MongoDB with encrypted fields and audit collections |
| **Infrastructure** | AWS with encrypted storage and private networking |

</details>

### 🤖 Prompt Factory
`AI`

**AI prompt and LLM security platform (in development)**
<sub>React.js · Node.js · Express.js · MongoDB · LLM services · OCR · AWS</sub>

- Turns an input image into a structured prompt that can regenerate the image.
- PIN-gated prompt access; a wrong PIN returns a deliberately different image.
- Multi-pass rendering and mismatch tracking in MongoDB to improve accuracy.

<details>
<summary><b>Architecture</b></summary>

| Layer | Details |
|---|---|
| **Input** | Image upload, analysis, OCR text extraction |
| **AI processing** | Visual analysis, structured prompts, refinement |
| **Security** | Access control and PIN verification |
| **Data** | Prompts, OCR data, mismatch history |
| **Learning** | Recurring pattern analysis |

</details>

### 🩺 ClinicFlow
`Healthcare` `Real-time`

**Multi-clinic healthcare operations platform**
<sub>React.js · Node.js · Express.js · MongoDB · Socket.IO · AWS EC2 and S3</sub>

- Scheduling, doctor rosters, medical inventory and billing across branches.
- Live queue and waiting list over Socket.IO for reception desks and doctor screens.
- Dashboards for footfall, revenue, doctor utilization and stock turnover.

<details>
<summary><b>Architecture</b></summary>

| Layer | Details |
|---|---|
| **Frontend** | Dashboards for Admin, Reception, Doctor, Inventory |
| **Real-time** | Socket.IO live queue and status |
| **API** | Express REST services, modular controllers |
| **Data** | MongoDB for patients, visits, stock, invoices |
| **Deployment** | AWS EC2 and S3 |

</details>

### 💬 ConnectHub
`Real-time`

**Real-time team chat and collaboration platform**
<sub>React.js · Node.js · Express.js · MongoDB · Socket.IO · AWS S3</sub>

- Channels, direct messages, typing indicators, online presence and read receipts.
- File sharing through S3 with secure, expiring links.
- JWT authentication with workspace-level roles and permissions.

<details>
<summary><b>Architecture</b></summary>

| Layer | Details |
|---|---|
| **Client** | React.js chat UI with optimistic updates |
| **Real-time** | Socket.IO rooms and namespaces |
| **API** | REST for history, search and uploads |
| **Data** | MongoDB for users, channels, messages |
| **Deployment** | AWS EC2 and S3 |

</details>

### 📹 CareConnect
`Healthcare` `Real-time`

**Telemedicine and online consultation platform**
<sub>React.js · Node.js · Express.js · MongoDB · WebRTC · Socket.IO · AWS</sub>

- Video consultations between patients and doctors with in-call chat.
- Slot booking, reminders and downloadable e-prescriptions.
- Consent and audit trail for every access to patient data.

<details>
<summary><b>Architecture</b></summary>

| Layer | Details |
|---|---|
| **Client** | React.js patient and doctor apps |
| **Signalling** | Socket.IO for WebRTC session setup |
| **Services** | Booking, Prescription, Notification modules |
| **Security** | JWT, RBAC, audit logging |
| **Data** | MongoDB with encrypted records |

</details>

### 🛒 ShopSphere
`E-commerce`

**Multi-vendor e-commerce marketplace**
<sub>React.js · Node.js · Express.js · MongoDB · Razorpay · AWS S3</sub>

- Vendor onboarding, product catalogue with search and filters, cart and checkout.
- Online payments, order tracking and refund handling.
- Admin analytics for sales, vendors and inventory.

<details>
<summary><b>Architecture</b></summary>

| Layer | Details |
|---|---|
| **Storefront** | React.js catalogue, cart and checkout |
| **Vendor panel** | Products, orders, payouts |
| **API** | Express services for catalogue, orders, payments |
| **Payments** | Razorpay with webhook verification |
| **Data** | MongoDB, images on S3 |

</details>

---

## 💼 Experience

**Senior Software Developer** · Infosys Limited - Pune Campus
<sub>Dec 2025 – Present</sub>
- Built a real-time chat system with React.js, Node.js and Socket.IO.
- Delivered REST APIs, WebSocket services, JWT authentication and role-based access.
- Deployed MERN apps on AWS EC2 and tuned production performance.

**Senior Web Developer** · Aabhyasa Technologies Pvt. Ltd., Varanasi
<sub>Nov 2021 – Nov 2025</sub>
- Managed and mentored 10 developers and set coding standards.
- Architected healthcare webinar platforms and enterprise SaaS products with secure data-access workflows.
- Led product design and AWS deployment; automation work cut document processing time by 50%.

**Software Developer** · Pride Solution, Prayagraj
<sub>Jun 2020 – Oct 2021</sub>
- Led 5 developers on ERP frontends, inventory trackers and role-based dashboards.
- Built data visualization for government COVID-19 tracking applications.
- Improved interaction speed by about 40% through state-management optimization.

**Software Developer** · Edunext Technologies Pvt. Ltd., Noida
<sub>Jun 2019 – Jun 2020</sub>
- Built responsive interfaces with HTML5, CSS3, JavaScript and Bootstrap, and improved page load performance.

**Software Developer** · Vapsoft Technologies Pvt. Ltd., Prayagraj
<sub>Oct 2015 – May 2019</sub>
- Built PHP and MySQL web apps with payment, SMS and email integrations, and applied XSS, CSRF and SQL injection protections.

---

## 🛠️ Skills

| | |
|---|---|
| **Frontend** <br/> React.js, JavaScript (ES6+), HTML5, CSS3, Bootstrap, Tailwind CSS | **Backend** <br/> Node.js, Express.js, REST APIs, WebSocket, Socket.IO |
| **Databases** <br/> MongoDB, MySQL, PostgreSQL, data modelling | **Security** <br/> JWT, RBAC, input validation, HIPAA and PHI safeguards, audit logging |
| **AI and LLM** <br/> Prompt engineering, image-to-prompt workflows, OCR, LLM application security | **Cloud and architecture** <br/> AWS EC2 and S3, modular and microservice design, real-time systems |

<div align="center">

![React](https://img.shields.io/badge/React-0F2A2B?style=flat-square&logo=react&logoColor=5FD3B0)
![Node.js](https://img.shields.io/badge/Node.js-0F2A2B?style=flat-square&logo=nodedotjs&logoColor=5FD3B0)
![Express](https://img.shields.io/badge/Express-0F2A2B?style=flat-square&logo=express&logoColor=5FD3B0)
![MongoDB](https://img.shields.io/badge/MongoDB-0F2A2B?style=flat-square&logo=mongodb&logoColor=5FD3B0)
![Socket.IO](https://img.shields.io/badge/Socket.IO-0F2A2B?style=flat-square&logo=socketdotio&logoColor=5FD3B0)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0F2A2B?style=flat-square&logo=postgresql&logoColor=5FD3B0)
![MySQL](https://img.shields.io/badge/MySQL-0F2A2B?style=flat-square&logo=mysql&logoColor=5FD3B0)
![Tailwind](https://img.shields.io/badge/Tailwind-0F2A2B?style=flat-square&logo=tailwindcss&logoColor=5FD3B0)
![AWS](https://img.shields.io/badge/AWS-0F2A2B?style=flat-square&logo=amazonwebservices&logoColor=5FD3B0)
![WebRTC](https://img.shields.io/badge/WebRTC-0F2A2B?style=flat-square&logo=webrtc&logoColor=5FD3B0)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0F2A2B&height=170&section=footer&text=Let's%20talk&fontColor=E6F1EF&fontSize=40&fontAlignY=65" alt="Let's talk" width="100%"/>

**Open to senior full stack roles and architecture-heavy projects.**

📧 [ersharaddubey@gmail.com](mailto:ersharaddubey@gmail.com) · 📞 [+91-8922096699](tel:+918922096699)

<sub>B.Tech, Kashi Institute of Technology, Varanasi (2015) · English (professional), Hindi (native)</sub>

</div>
