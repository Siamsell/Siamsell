<h1 align="center">Siham Sellami</h1>

<p align="center">
  <b>Software Engineering Master's student · Full Stack Developer</b><br/>
  I design reliable web applications and distributed architectures,<br/>
  and explore applied AI (NLP, GANs for medical imaging).
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sellami-siham-a5b092333"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://portfolio-five-delta-oh0wzbn380.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-9B72CF?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:sihamsella9@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About me

- 🎓 Master's in **Software Engineering** (UMBB, Boumerdès, Algeria) after a Bachelor's in Computer Science
- 🏗️ Focus: **software architecture, microservices, distributed systems**
- 🤖 Exploring: **deep learning for medical imaging** (GANs) and **NLP**
- 💼 Experience: internships at **Sonatrach** (PostgreSQL database design) and **Annabib** (ERP purchase request system)
- 🌍 Languages: Arabic, Kabyle, French (professional), English (working)
- 📫 Open to internship and junior engineering opportunities

---

## Featured projects

### 🧩 Distributed Microservices Platform
A distributed architecture with **6 service instances deployed across 9 servers**, built for high availability and scalability.

- Service discovery, health checks, load balancing and fault tolerance
- Asynchronous, event-driven communication with **RabbitMQ** to keep independent databases in sync, which reduces coupling between services
- Single entry point through an API gateway

```
Client ──► Traefik (gateway / load balancer)
              │
              ├──► Service A (x instances) ──┐
              ├──► Service B (x instances) ──┼──► RabbitMQ (events)
              └──► Service C (x instances) ──┘        │
                         │                             ▼
                   Consul (discovery + health)   Synchronized DBs (MySQL)
```

**Stack:** `Node.js` `Traefik` `Consul` `RabbitMQ` `MySQL` `Docker` `REST`
**Links:** [Code](https://github.com/Siamsell/NOM-DU-DEPOT-MICROSERVICES)

---

### 📰 Fake News Detection (NLP)
A text classifier that detects misinformation using classic NLP techniques.

- Preprocessing: tokenization, stop-word removal, lemmatization
- Compared **SVM, Naive Bayes and Logistic Regression** to pick the best model
- Served through a small **Flask** web interface

**Stack:** `Python` `Scikit-learn` `NLTK` `Pandas` `Flask`
**Links:** [Code](https://github.com/Siamsell/NOM-DU-DEPOT-FAKE-NEWS)

---

### 🩻 Medical Image GAN (Final Year Project)
A GAN-based pipeline that generates **high-resolution, anatomically accurate CT images** to support diagnostic research.

- Models: **DCGAN** and **StyleGAN3**
- Built and trained with PyTorch

**Stack:** `Python` `PyTorch` `DCGAN` `StyleGAN3`
**Links:** [Code](https://github.com/Siamsell/medicale_IMG-with-deepLearning_model-gan) · [Live](https://medical-image-gan.netlify.app/)

---

### 🎓 Academy Platform
An online learning platform with courses and student progress tracking.

**Stack:** `Full Stack`
**Links:** [Live](https://siamsell.github.io/Academy-Platform/)

---

### 🏢 Purchase Request System (ERP, Annabib internship)
An internal procurement workflow: request submission, approval, tracking and **role-based access**. *(Private, internal deployment.)*

**Stack:** `Node.js` `Express` `MySQL` `JavaScript` `AJAX` `Bootstrap` · MVC architecture

---

## Tech stack

| Domain | Tools |
|---|---|
| **Languages** | Python, JavaScript, Java, C, C++, R, OCaml |
| **Frontend** | React, HTML, CSS, AJAX, XML |
| **Backend** | Node.js, Express, Django, Flask, REST APIs, MVC |
| **Databases** | PostgreSQL, MySQL, SQL, SQLite |
| **Architecture** | Microservices, API Gateway, Event-Driven, Design Patterns, UML, System Design |
| **Distributed** | Traefik, Consul, RabbitMQ, Docker |
| **ML / AI** | PyTorch, TensorFlow, Scikit-learn, NLTK, Pandas, GANs |
| **Tools** | Git, GitHub, Agile / Scrum |

---

## Currently

- Deepening **software architecture** and **microservices** in my Master's program
- Working on **GAN models for medical imaging**
- Improving my projects with **tests, CI and documentation**

---

<p align="center">
  <i>Let's build something reliable together.</i><br/><br/>
  <a href="https://www.linkedin.com/in/sellami-siham-a5b092333">LinkedIn</a> ·
  <a href="mailto:sihamsella9@gmail.com">Email</a> ·
  <a href="https://portfolio-five-delta-oh0wzbn380.vercel.app/">Portfolio</a>
</p>
