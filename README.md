<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5967D9,100:202938&height=160&section=header&text=NoteVault&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Academic%20Study%20Sanctuary%20·%20DEFINE%204.0&descAlignY=58&descColor=bcc2ff" />

<br/>

<p><em>Official project submission for DEFINE 4.0 — The World's Realest Hackathon</em></p>

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Prototype-notevault--one.vercel.app-5967D9?style=for-the-badge)](https://notevault-one.vercel.app/)
[![Demo Video](https://img.shields.io/badge/▶%20Demo%20Video-Watch%20Now-EA4335?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1QJPD5MsJhyVz5dpvw35PT-IN5sosWzjl/view?usp=drivesdk)
[![Repo](https://img.shields.io/badge/GitHub-DEFINE4.0-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prohaneen/DEFINE4.0)

</div>

---

## 🏷️ Submission Info

| | |
| :--- | :--- |
| **Hackathon** | DEFINE 4.0 |
| **Team** | The Unwireds |
| **Track** | 🎨 Design |

---

## 👥 Team Members

<div align="center">

| Name | Role | GitHub | LinkedIn |
| :---: | :---: | :---: | :---: |
| **Haneen Ershad** | Lead UI/UX Designer | [![GitHub](https://img.shields.io/badge/@prohaneen-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prohaneen) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prohaneen/) |
| **Muhammed Fazil H** | UI Designer | [![GitHub](https://img.shields.io/badge/@fazil--pi-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/fazil-pi) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammed-fazil-h-196b24304/) |
| **Adish S** | UI Designer | [![GitHub](https://img.shields.io/badge/@Adish--aster-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Adish-aster) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adish-s-166aa332a/) |

</div>

---

## 📌 Overview

NoteVault is a high-fidelity UI/UX design concept for a centralised academic learning platform. This submission presents the complete visual design, layout, interaction patterns, and user experience for a platform that helps students discover, organise, and access their scattered study resources in one beautiful, distraction-free environment.

> **Note:** This is a design track submission. The repository contains a fully interactive, browser-rendered prototype built with React and Tailwind CSS, using rich dummy data to demonstrate every screen and interaction.

---

## 🎯 Problem Statement

Students' study materials are fragmented across dozens of platforms — university portals, YouTube, GitHub, Google Drive, and messaging apps. There is no single, beautiful interface designed specifically for organising academic resources.

| Who is affected? | Why does design matter? |
| :--- | :--- |
| University students, entrance exam aspirants, and self-learners | Existing tools like Notion or Google Drive are generic — they lack visual clarity for academic content. A student cannot instantly tell apart a PDF lecture, a YouTube tutorial, and a GitHub repo at a glance. |

---

## 💡 Design Solution

We designed a unified **"Academic Study Sanctuary"** — an editorial, focused, and visually expressive interface that solves four core user needs:

| Pillar | Design Solution |
| :--- | :--- |
| 🔍 **Find** | Federated search bar with instant filter pills (PDFs, Videos, GitHub, PYQs, Textbooks) |
| 🗂️ **Organise** | Subject-based "Vault" cards with topic-level drill-down and progress tracking |
| 🧭 **Navigate** | A persistent sidebar and a "Focus Panel" split-view for resource details |
| 📖 **Access** | Embedded resource previews and a seamless "Open Resource" CTA |

---

## ✨ Design Highlights

### 1. Editorial "Book Cover" Cards
Every resource renders as a physical book cover with a unique mesh-gradient background based on its type *(e.g. warm pink for PDFs, amber for videos, green for GitHub repos)*. Features a 3D isometric tilt animation on hover.

### 2. Distraction-Free Focus Panel
A slide-in panel with the resource's full metadata, read/watch progress bar, contextual highlights, and a prominent CTA — without ever leaving the current view.

### 3. Active Recall Sprint UI
Dedicated flashcard drill interface with card-flip animations, difficulty ratings (Easy / Hard / Missed), and spaced repetition progress — designed for exam preparation.

### 4. AI Study Guide Interface
A glassmorphic card showcasing the UI pattern for AI-generated "Key Takeaways" and resource summaries.

### 5. Design System & Tokens

| Token | Value |
| :--- | :--- |
| **Background** | `#F7F5F0` Warm Paper |
| **Text Primary** | `#131c2a` Ink Navy |
| **Accent** | `#5967D9` Indigo |
| **Display Font** | Outfit 700 |
| **Body Font** | Plus Jakarta Sans 400/600 |
| **Border Radius** | 16px – 24px |
| **Shadow** | Layered soft shadows + glassmorphism |

---

## 🖥️ Screens Designed

- **Dashboard** — Greeting, milestone banner, active recall sprint, vault stats, subject carousel
- **Library View** — Filter tabs, resource grid, progress indicators
- **Subject View** — Topic navigator, resource list with progress bars
- **Saved Vault** — Bookmarked resources with format filters
- **Resource Detail** — Focus Panel with metadata sidebar, AI study guide card
- **Flashcard Drill Modal** — Animated flashcard quiz with spaced repetition UI
- **Add Resource View** — Form to add a new resource to a subject

---

## 🚀 Run Locally

```bash
# Clone the repository
git clone https://github.com/prohaneen/DEFINE4.0.git
cd DEFINE4.0

# Install dependencies
npm install --legacy-peer-deps

# Start the prototype
npm run dev
```

Open your browser at `http://localhost:3000`

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:202938,100:5967D9&height=100&section=footer" />
</div>
