<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Dharoon%20Balajii&fontSize=48&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=Builder.%20Thinker.%20Breaker%20of%20things.&descAlignY=62&descSize=16&descColor=c792ea" alt="Dharoon Balajii. Builder. Thinker. Breaker of things."/>
</div>

<p align="center">
  <img src=".github/assets/terminal.svg" alt="Animated terminal. whoami: Dharoon Balajii, CSE at VIT Vellore. ls projects: gitpath, raksha-thunai, learnflow, safe-step, socrates-aid."/>
</p>

<p align="center">
  <a href="https://www.dharoonbalajii.space"><img src="https://img.shields.io/badge/Portfolio-c792ea?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMGYwYzI5IiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMiAxMmgyME0xMiAyYTE1IDE1IDAgMCAxIDAgMjBNMTIgMmExNSAxNSAwIDAgMCAwIDIwIi8+PC9zdmc+" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/dharoonbalajii/"><img src="https://img.shields.io/badge/LinkedIn-302b63?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDAgMS0yLjA2My0yLjA2NSAyLjA2NCAyLjA2NCAwIDEgMSAyLjA2MyAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+" alt="LinkedIn"/></a>
  <a href="mailto:dharoonbalajiie@gmail.com"><img src="https://img.shields.io/badge/Email-302b63?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

## <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" width="30" alt="👋"/> Hey, I'm Dharoon

<img align="right" width="340" src=".github/assets/coder.svg" alt="Animated illustration of Dharoon coding at night with headphones on, code typing out on the monitor, a steaming coffee and a rubber duck on the desk."/>

A second-year CSE student at **VIT Vellore** who builds things before fully knowing how, and learns the rest on the way.

Lately I care most about the parts of AI products you don't see: background jobs, databases, and the security that keeps them fast, cheap and safe.

- 🔭 Building **Gitpath**: any GitHub repo in, an interactive course out
- 🔐 Security habits: rate limits, bot checks, encrypted secrets, scans in CI
- 🏆 Won **Best Fresher** at a hackathon
- 💬 Ask me about BullMQ, Prisma, Flutter, or why your API needs a rate limit

<br clear="right"/>

## <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f680/512.gif" width="30" alt="🚀"/> Featured work

### 🎓 Gitpath

**Give it any GitHub repository and it builds an interactive course: lessons, quizzes and an AI tutor.**

The order is the trick. The code is analysed **without AI first**, then the model writes the course **once per repo** and it's stored. Every learner after that is served from the database, so it stays fast for users and cheap to run.

```mermaid
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#302b63", "primaryTextColor": "#ffffff", "primaryBorderColor": "#c792ea", "lineColor": "#c792ea", "fontSize": "14px"}}}%%
flowchart LR
    A["Any GitHub repo"] --> B["Static analysis<br/>no AI"]
    B --> C[("Code graph<br/>Postgres")]
    C --> D["AI writes the course<br/>once per repo"]
    D --> E["Lessons, quizzes, tutor<br/>served from cache"]
```

- **Backend:** background jobs with BullMQ and Redis, Postgres with Prisma, Docker, CI with GitHub Actions
- **Security:** rate limiting, Cloudflare Turnstile to block bots, encryption for stored secrets, GitHub OAuth login, a security scan in the CI pipeline

![Next.js](https://img.shields.io/badge/Next.js-24243e?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-24243e?style=flat-square&logo=typescript&logoColor=white)
![BullMQ + Redis](https://img.shields.io/badge/BullMQ_+_Redis-24243e?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-24243e?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-24243e?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-24243e?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-24243e?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare Turnstile](https://img.shields.io/badge/Turnstile-24243e?style=flat-square&logo=cloudflare&logoColor=white)

<sub>🔒 Source is private. Happy to demo it.</sub>

### 🚨 Raksha Thunai

**A women's safety app our team built. I wrote most of the code.**

You trigger it with a gesture and it starts listening to the surroundings. It understands distress in Indian languages, including mixed ones like Tanglish, then alerts guardians with your live location.

`gesture` → `listen` → `spot distress` → `alert guardians` → `share live location`

- **Built:** the Flutter app and the TypeScript backend
- **Security:** it handles people's locations and emergencies, so every route is protected: authentication, OTP verification, and validation on every request

![Flutter](https://img.shields.io/badge/Flutter-24243e?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-24243e?style=flat-square&logo=dart&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-24243e?style=flat-square&logo=typescript&logoColor=white)

### 🧠 LearnFlow

**An AI learning platform that turns a complex topic into a structured learning journey.**

It breaks a subject into subtopics, finds high-quality educational videos ranked by relevance, popularity and engagement, and builds a personalised YouTube playlist in your preferred language. Students spend their time learning instead of searching.

`topic` → `subtopics` → `rank the best videos` → `playlist in your language`


### 💚 AI Student Wellbeing Platform

**Mental wellness support built for campuses with thousands of students.**

Students get emotional support through AI conversations, mood tracking and personalised wellbeing recommendations. Licensed therapists get structured reports so they can assess and step in faster, and institutions can spot at-risk students early and lighten the load on counselling teams.

`talk it out` → `track mood` → `personal recommendations` → `report for therapists`

## <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f6e0_fe0f/512.gif" width="30" alt="🛠️"/> More builds

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🦺 Safe Step</h4>
      A wearable that detects impacts and falls and alerts caretakers on WhatsApp in seconds, backed by a cloud service and a web dashboard.
      <br/><br/>
      <sub>🔗 <a href="https://mdp2026.netlify.app/">mdp2026.netlify.app</a></sub>
    </td>
    <td width="50%" valign="top">
      <h4>🦉 Socrates Aid</h4>
      An AI tutor that guides students with questions instead of handing them answers, with a teacher dashboard and a Python analytics module.
      <br/><br/>
      <sub>🔗 <a href="https://github.com/DharoonBalajii/socrates-aid-app">socrates-aid-app</a></sub>
    </td>
  </tr>
</table>

## <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4bb/512.gif" width="30" alt="💻"/> Toolbox

<table>
  <tr>
    <td><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,python,java,cpp,cs,dart" alt="TypeScript, Python, Java, C++, C#, Dart"/></td>
  </tr>
  <tr>
    <td><b>Backend & data</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,nextjs,postgres,prisma,redis,supabase" alt="Node.js, Next.js, PostgreSQL, Prisma, Redis, Supabase"/></td>
  </tr>
  <tr>
    <td><b>Apps & web</b></td>
    <td><img src="https://skillicons.dev/icons?i=flutter,react,tailwind,html" alt="Flutter, React, Tailwind CSS, HTML"/></td>
  </tr>
  <tr>
    <td><b>Cloud & shipping</b></td>
    <td><img src="https://skillicons.dev/icons?i=aws,docker,githubactions,cloudflare,git" alt="AWS, Docker, GitHub Actions, Cloudflare, Git"/></td>
  </tr>
</table>

## <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f40d/512.gif" width="30" alt="🐍"/> Contributions

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DharoonBalajii/DharoonBalajii/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DharoonBalajii/DharoonBalajii/output/github-contribution-grid-snake.svg">
    <img alt="Snake eating my GitHub contribution grid" src="https://raw.githubusercontent.com/DharoonBalajii/DharoonBalajii/output/github-contribution-grid-snake.svg">
  </picture>
</div>

## <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f91d/512.gif" width="30" alt="🤝"/> Let's build something

Got an idea, a hackathon, or a bug that needs breaking? See more of my work at [dharoonbalajii.space](https://www.dharoonbalajii.space), or find me on [LinkedIn](https://www.linkedin.com/in/dharoonbalajii/) or at [dharoonbalajiie@gmail.com](mailto:dharoonbalajiie@gmail.com).

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" alt=""/>
</div>
