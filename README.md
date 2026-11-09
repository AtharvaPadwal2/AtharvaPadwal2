<div align="center">

<a href="https://github.com/AtharvaPadwal2">
<img src="banner.svg" width="100%" alt="Atharva Padwal — Full-stack, security, cloud and applied AI" />
</a>

<a href="https://github.com/AtharvaPadwal2">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=21&duration=2600&pause=850&color=EA1A85&center=true&vCenter=true&width=850&height=52&lines=Building+useful+products+from+idea+to+deployment.;IT+engineering+student+%7C+Mumbai%2C+India;Creator+of+Project+Unwind+%F0%9F%8C%BF+%26+ARTifact+%F0%9F%9B%8B;React+%C2%B7+Node.js+%C2%B7+PostgreSQL+%C2%B7+Three.js;Learning+security%2C+cloud+and+applied+AI." alt="Animated introduction" />
</a>

<br/>

<a href="mailto:atharvapadwal520@gmail.com"><img src="https://img.shields.io/badge/OPEN%20TO-MUMBAI%20INTERNSHIPS-EA1A85?style=for-the-badge&labelColor=0A1033&logo=target&logoColor=EA1A85" alt="Open to Mumbai internships" /></a>
<a href="https://project-unwind-mu.vercel.app/"><img src="https://img.shields.io/badge/LIVE-PROJECT%20UNWIND-254AA5?style=for-the-badge&labelColor=0A1033&logo=vercel&logoColor=white" alt="Project Unwind" /></a>
<a href="https://ar-tifact-six.vercel.app/"><img src="https://img.shields.io/badge/LIVE-ARTifact-EA1A85?style=for-the-badge&labelColor=0A1033&logo=vercel&logoColor=white" alt="ARTifact" /></a>
<a href="https://github.com/AtharvaPadwal2"><img src="https://komarev.com/ghpvc/?username=AtharvaPadwal2&style=for-the-badge&color=254AA5&label=VISITORS&labelColor=0A1033" alt="Profile views" /></a>

<br/><br/>

**[About](#about)** &nbsp;•&nbsp; **[Projects](#projects)** &nbsp;•&nbsp; **[Stack](#stack)** &nbsp;•&nbsp; **[Stats](#stats)** &nbsp;•&nbsp; **[Journey](#journey)** &nbsp;•&nbsp; **[Contact](#contact)**

</div>

<br/>

<a id="about"></a>
## ✦ About me

<table>
<tr>
<td width="52%" valign="top">

### Hello, I'm Atharva 👋

I'm an Information Technology engineering student at Atharva College of Engineering, Mumbai, who enjoys turning rough ideas into useful, dependable software.

I like working across the whole product loop: understanding the problem, designing the system, building the interface and API, deploying it, then learning from real users.

I'm especially interested in full-stack development, application security, cloud fundamentals, interactive 3D experiences, and practical AI.

</td>
<td width="48%" valign="top">

```js
const atharva = {
  location: "Mumbai, India",
  role: "IT engineering student",
  builds: ["web apps", "APIs", "3D interfaces"],
  mainStack: ["React", "Node.js", "PostgreSQL"],
  exploring: ["cloud", "security", "RAG", "DevOps"],
  practising: "DSA with Java",
  openTo: "software internships & collaborations",
};
```

</td>
</tr>
</table>

<div align="center">

**Build with curiosity. Ship with care. Improve with feedback.**

</div>

<br/>

<img src="divider.svg" width="100%" alt="" />

<a id="projects"></a>
## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🌿 Project Unwind
**Privacy-first, non-medical mental wellness platform.**

Journaling, wellness tracking, self-reflection, community support, real-time chat, session workflows and an AI companion built with a team.

`React` `Vite` `Node.js` `Express` `PostgreSQL` `Socket.IO` `JWT` `Cloudinary` `Neon`

<a href="https://project-unwind-mu.vercel.app/"><img src="https://img.shields.io/badge/EXPLORE-UNWIND-EA1A85?style=for-the-badge&labelColor=0A1033&logo=vercel&logoColor=white" alt="Explore Project Unwind" /></a>

</td>
<td width="50%" valign="top">

### 🛋️ ARTifact
**AR furniture discovery and visualization app.**

Browse a furniture catalogue, preview 3D models in your space, and manage a workspace/history experience through an AR-enabled interface.

`React` `Vite` `model-viewer` `Node.js` `Express` `MongoDB Atlas` `Appwrite`

<a href="https://ar-tifact-six.vercel.app/"><img src="https://img.shields.io/badge/EXPLORE-ARTifact-254AA5?style=for-the-badge&labelColor=0A1033&logo=vercel&logoColor=white" alt="Explore ARTifact" /></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ♟️ ChessRAG
**A retrieval-augmented chess tutor and analysis board.**

Explore **2,803** opening records, replay **19,113** validated games, learn with cited lessons, and play Stockfish across four difficulty levels on interactive 2D/3D boards.

`Vue 3` `Three.js` `FastAPI` `Stockfish` `Supabase` `pgvector` `FastEmbed`

</td>
<td width="50%" valign="top">

### 📓 Journal Insights
**An NLP experiment for emotion-aware reflections.**

A Streamlit interface for emotion classification, sentiment, keywords and reflection prompts. Tuned TF-IDF + LinearSVC reached **90.64%** validation accuracy.

`Python` `scikit-learn` `TF-IDF` `LinearSVC` `Streamlit`

</td>
</tr>
</table>

<details>
<summary><b>🔍 Project Unwind: architecture and lessons</b></summary>

<br/>

```mermaid
flowchart LR
    U([User]) --> FE["React + Vite<br/>Vercel"]
    FE -- "REST + JWT" --> API["Node + Express<br/>Render"]
    FE -- "WebSocket" --> RT["Socket.IO<br/>real-time chat"]
    RT --> API
    API --> DB[("PostgreSQL<br/>Neon")]
    API --> CL["Cloudinary<br/>media"]
    API --> BR["Brevo<br/>email"]
    FE -.-> PH["PostHog<br/>analytics"]
    classDef blue fill:#254AA5,stroke:#0A1033,color:#fff
    classDef pink fill:#EA1A85,stroke:#0A1033,color:#fff
    class FE,API,RT blue
    class DB,CL,BR pink
```

| Area | What I worked on |
|:--|:--|
| 🔑 **Accounts** | Email verification, password recovery, Google OAuth, access/refresh tokens and protected routes |
| 📔 **Journaling** | Journal lifecycle management and PIN-based journal locking |
| 📈 **Wellness** | Mood, sleep, habit, energy and water tracking; DASS-21 self-assessment and PDF output |
| 💬 **Community** | Posts, comments, likes, real-time chat, direct messages and reporting workflows |
| 🛡️ **Administration** | User/report management, decision workflows, testimonials and audit logs |
| 📅 **Sessions** | Booking requests, approval flows, scheduling and session-handler tools |

> **Lesson:** shipping features is only one part of the work. Sessions, permissions, database limits, real-time connections and user feedback matter just as much.

<sub>Unwind is a wellness companion, not a medical diagnosis or treatment service. AI companion development is a team effort.</sub>

</details>

<details>
<summary><b>🧩 More things I've built or explored</b></summary>

<br/>

| Project | Focus |
|:--|:--|
| 🏏 **RR Scouting Intelligence** | Cricket scouting dashboard with Python, Streamlit, Pandas and explainable comparisons |
| 🤖 **M.O.L.E. Rover** | Mine mapping and emergency response concept; SIH internal top-50 team |
| 🎯 **BallTrace DRS** | Cricket ball-tracking API experiments with FastAPI and frontend overlays |
| ☕ **DSA in Java** | Arrays, strings, searching and sorting practice |
| ⚙️ **DevOps practice** | Git workflows, CI/CD, containers and infrastructure automation |
| 🧩 **Smaller builds** | Chat app, Photobooth, full-stack Todo, Pawdcast PetCare and more |

</details>

<br/>

<img src="divider.svg" width="100%" alt="" />

<a id="stack"></a>
## 🧰 My stack

<div align="center">

<img src="https://skillicons.dev/icons?i=js,ts,java,python,html,css,react,vue,nextjs,nodejs,express,fastapi,postgres,mongodb,supabase,threejs,git,github,githubactions,docker,linux&perline=10" alt="Technology icons" />

<br/><br/>

<img src="https://img.shields.io/badge/Frontend-React%20%7C%20Vue%20%7C%20Vite-EA1A85?style=flat-square&labelColor=0A1033" alt="Frontend stack" />
<img src="https://img.shields.io/badge/Backend-Node%20%7C%20Express%20%7C%20FastAPI-254AA5?style=flat-square&labelColor=0A1033" alt="Backend stack" />
<img src="https://img.shields.io/badge/Data-PostgreSQL%20%7C%20MongoDB%20%7C%20pgvector-EA1A85?style=flat-square&labelColor=0A1033" alt="Data stack" />
<img src="https://img.shields.io/badge/Interactive-Three.js%20%7C%20model--viewer-254AA5?style=flat-square&labelColor=0A1033" alt="Interactive stack" />

</div>

<br/>

<table>
<tr>
<td width="33%" valign="top">

**Frontend**

React · Vite · Vue 3 · React Router · responsive UI · state and component design

</td>
<td width="33%" valign="top">

**Backend & security**

Node.js · Express · FastAPI · REST · Socket.IO · JWT · OAuth · bcrypt · Zod · Helmet · CORS

</td>
<td width="33%" valign="top">

**AI, data & 3D**

Pandas · scikit-learn · TF-IDF · RAG · FastEmbed · pgvector · Three.js · Stockfish

</td>
</tr>
</table>

<details>
<summary><b>☁️ Shipping, cloud and workflow</b></summary>

<br/>

Git · GitHub · GitHub Actions · Docker · Linux · Vercel · Render · Neon · Supabase · UptimeRobot · PostHog · k6 · Ansible · Nginx · Kubernetes fundamentals · AWS Cloud Practitioner Essentials

</details>

<br/>

<a id="stats"></a>
## 📊 GitHub dashboard

<div align="center">

<img src="https://streak-stats.demolab.com?user=AtharvaPadwal2&hide_border=true&background=00000000&ring=EA1A85&fire=EA1A85&currStreakLabel=EA1A85&sideLabels=8C98C4&currStreakNum=8C98C4&sideNums=8C98C4&dates=8C98C4" alt="GitHub contribution streak" />

<br/><br/>

<img src="https://raw.githubusercontent.com/AtharvaPadwal2/AtharvaPadwal2/output/snake.svg" width="96%" alt="Contribution snake" />

<br/>

<sub>The streak card is powered by an external service and may load slowly. The snake is generated by a GitHub Action in this repo.</sub>

</div>

<br/>

## 🧊 Build map

<div align="center">

<img src="build-map.svg" width="100%" alt="Build map: frontend, backend, cloud and AI feeding into useful products, reliable systems and real-world learning" />

</div>

<br/>

<img src="divider.svg" width="100%" alt="" />

<a id="journey"></a>
## 🧭 Learning journey

```mermaid
timeline
    title Things I've shipped and learned
    Learning : Core Java (Internshala)
             : React, Redux, Next.js, Node.js (Udemy)
    Cloud : AWS Cloud Practitioner Essentials
    Teamwork : SIH internal top-50 (M.O.L.E. Rover)
    Shipping : Project Unwind built, deployed and tested with real users
```

- ☁️ **AWS Cloud Practitioner Essentials:** completed through AWS Training & Certification; this is a course completion, distinct from the certification exam.
- ⚛️ **React / Redux / Next.js / Node.js:** coursework through Udemy.
- ☕ **Core Java:** coursework through Internshala.
- 🏅 **SIH internal top-50:** team work on the M.O.L.E. Rover concept.

## 🎯 What I'm working towards

| | Goal |
|:-:|:--|
| 🏗️ | Build stronger software with clearer architecture, thoughtful APIs and dependable UX |
| 🔒 | Understand production: secure deployments, monitoring, performance and database operations |
| 🧠 | Apply AI with purpose and evaluate the limits of ML and retrieval features |
| 📐 | Keep Java DSA, databases, networking and system design fundamentals sharp |
| 🤝 | Learn with a team through internships, code reviews and practical collaboration |

<br/>

<a id="contact"></a>
## 🤝 Let's build something

I'm interested in **Mumbai-based software development internships**, practical collaborations, and conversations about building useful products.

<div align="center">

<a href="mailto:atharvapadwal520@gmail.com"><img src="https://img.shields.io/badge/EMAIL-LET'S%20CONNECT-EA1A85?style=for-the-badge&labelColor=0A1033&logo=gmail&logoColor=EA1A85" alt="Email Atharva" /></a>
<a href="https://github.com/AtharvaPadwal2"><img src="https://img.shields.io/badge/GITHUB-ATHARVAPADWAL2-254AA5?style=for-the-badge&labelColor=0A1033&logo=github&logoColor=white" alt="Atharva's GitHub" /></a>
<a href="https://project-unwind-mu.vercel.app/"><img src="https://img.shields.io/badge/TRY-PROJECT%20UNWIND-EA1A85?style=for-the-badge&labelColor=0A1033&logo=vercel&logoColor=white" alt="Try Project Unwind" /></a>

<br/><br/>

<img src="footer.svg" width="100%" alt="Animated pink and blue wave footer" />

</div>

<!-- Visuals use external image services. GitHub may cache them or render them differently over time. -->
