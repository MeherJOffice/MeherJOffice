<!-- Profile README for a sleek, creative look (works out of the box) -->
<!-- Put this file in a repo named exactly like your GitHub username:
     github.com/YOUR_USERNAME/YOUR_USERNAME -->

<p align="center">
  <img src="https://img.shields.io/badge/Davanci%20Ink-%F0%9F%8E%A8%20Game%20%26%20Automation%20Lab-111?style=for-the-badge" alt="Davanci Ink">
</p>

<h1 align="center">Meher “Davanci” — Game Dev • Tools • Automation</h1>

<p align="center">
  <b>Unity / Cocos • Editor Tools • CI & Automation • Flutter</b><br/>
  Paris (Île-de-France) · FR / EN
</p>

<p align="center">
  <img alt="" src="https://svg-banners.vercel.app/api?type=glitch&text1=DAVANCI%20LAB&width=1000&height=140"/>
</p>

<p align="center">
  <a href="#-live-terminal">Terminal</a> •
  <a href="#-signature-projects">Projects</a> •
  <a href="#-stack-map">Stack Map</a> •
  <a href="#-toolbox">Toolbox</a> •
  <a href="#-contact">Contact</a> •
  <a href="#-français">FR</a>
</p>

---

## 💻 Live Terminal

> I build **robust pipelines** and **editor tools** so teams ship faster.

```bash
$ whoami
meher_davanci  # Senior Game Developer & Automation Engineer

$ interests --top
Unity-Tools  Cocos-CI  Jenkins-AutoGen  URP-Perf  EditorUX  Flutter

$ now
🛠  Building AI-assisted CV/Letter generator (Flutter + Node Proxy)
🧪 Prototyping Unity Editor extensions (TMP localization, screenshot kit)
🚀 Hunting Unity tools/SDK roles in Paris / remote-FR

$ motto
"Ship clean. Automate boring. Never block creatives."
🎯 Signature Projects
Portfolio-style cards. Links work as placeholders (they won’t 404).

Project	What it is	Tech
Unity Tools Pack (Editor)	Addressables helpers, TMP i18n, screenshot generator	C# · Editor · URP · Addressables · Repo
Cocos Build Orchestrator	Deterministic iOS/Android/Xcode outputs from Cocos 3.x	Node/TS · Python · Xcode · Repo
Jenkins Auto-Gen	Monorepo pipeline for Unity/Cocos/Flutter, dynamic engine paths	Groovy · Go · Python · Repo
Rage Panda (Mobile)	Mobile Unity game, URP optimizations, IAP, analytics, CI	Unity 6 · C# · Mobile · Repo

<p align="center"> <img src="https://img.shields.io/badge/Showreel-1%3A30%20min-8A2BE2?style=for-the-badge&logo=youtube" alt="Showreel"> </p>
🗺 Stack Map
mermaid
Copy code
graph LR
  A[Unity 6 / C#] --- B[Editor Tools<br/>Addressables / TMP / URP]
  A --- C[Mobile Builds<br/>iOS/Android]
  D[Cocos Creator 2.x/3.x] --- C
  C --> E[Fastlane / Xcode 16]
  B --> F[Automation Scripts]
  F --> G[Jenkins / CLI Tools (Go/Python/TS)]
  G --> H[Artifacts / Stores]
  I[Flutter] --> J[Tools & Apps]
  J --> H
🧰 Toolbox
Core:
Unity 6 · Cocos Creator 2.x/3.x · C# · Golang · Python · TypeScript/Node
URP · Addressables · TMP · Flutter

Build & Ops:
Jenkins · Fastlane · Xcode 16 · Gradle · Docker · VMware · Bash/Zsh

<p> <img src="https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white"/> <img src="https://img.shields.io/badge/Unity-000000?logo=unity&logoColor=white"/> <img src="https://img.shields.io/badge/Cocos-1D1D1D"/> <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black"/> <img src="https://img.shields.io/badge/Golang-00ADD8?logo=go&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"/> </p>
🧪 Tiny Showcase
A 12-line Unity Editor snippet I actually use.

csharp
Copy code
// Snap selected objects to grid (0.5f) — saves minutes every session.
using UnityEditor; using UnityEngine;
public class Snapper { [MenuItem("Davanci/Snap to Grid _%g")]
static void Do(){ foreach(var t in Selection.transforms){
  var p=t.position; p.x=Mathf.Round(p.x*2)/2f; p.y=Mathf.Round(p.y*2)/2f; p.z=Mathf.Round(p.z*2)/2f; t.position=p;
}}}
🤝 Contact
✉️ Email: meher.davanci(at)proton.me

💼 LinkedIn: https://linkedin.com/ (add your handle)

🌐 Portfolio: https://davanci-ink.dev (example)

🕹 itch.io: https://itch.io/ (add your handle)

<p align="center"> <img src="https://img.shields.io/badge/Open_to-Unity%20Tools%2FSDK%20%7C%20Gameplay%20%7C%20Tech%20Lead-444?style=for-the-badge"/> </p>
<details id="-français"> <summary><b>🇫🇷 Version courte (FR)</b></summary>
Développeur de jeux & ingénieur automatisation (Unity & Cocos).
Je conçois des outils éditeur et des pipelines (Jenkins/Go/Python) pour livrer des jeux mobiles/Desktop de manière fiable. Basé à Paris.
Ouvert à des rôles Unity Tools/SDK/Gameplay.

Points forts : URP perf, Addressables, localisation TMP, CI reproductible, Xcode/Gradle.

Objectif : mettre la technique au service des équipes créatives, sans friction.

</details> <p align="center"> <sub>Last updated: 2025-10-26</sub> </p> ```
