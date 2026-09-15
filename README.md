<div align="center">

<img src="./assets/dev-hero.svg" alt="Simon at work" width="100%"/>

<br/>

<a href="https://github.com/Gr8vybs">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Simon+Afolayan+%F0%9F%91%8B;Full-Stack+Developer;DevOps+%26+Infrastructure+Engineer;Building+tech+for+local+impact+%F0%9F%87%B3%F0%9F%87%AC" alt="Typing SVG" />
</a>

<p>
  I build practical, production-grade software — from fintech and healthtech platforms serving Nigerian communities, to automated infrastructure that keeps things running.
</p>

<a href="https://linkedin.com/in/simon-afolayan"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:simonafolayan04@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/Gr8vybs"><img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</div>

<br/>

## 🧭 About Me

- 🔭 Currently rebuilding **WardLink NG**, an offline-first clinical handoff app, from a phone-only dev workflow
- 🌍 Focused on financial inclusion and healthcare access across Nigeria
- 🛠️ Comfortable across the stack: frontend, backend, databases, and the infrastructure that ships it all
- 📱 Yes — I build production systems entirely from an Android device (Acode + Alpine proot, no local Docker/Terraform/Helm binaries)
- ⚡ Fun fact: I've debugged Kubernetes and Terraform without ever opening a laptop terminal

<br/>

## 🔧 Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,py,nextjs,react,tailwind,nodejs,nestjs,postgres,sqlite,prisma,docker,kubernetes,terraform,githubactions,redis,aws,linux&theme=dark" alt="Tech stack icons"/>
</div>

<br/>

<table align="center">
<tr>
<td valign="top" width="33%">

**Languages & Frameworks**
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</td>
<td valign="top" width="33%">

**Infrastructure & DevOps**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/-Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</td>
<td valign="top" width="33%">

**Data & Auth**
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![NextAuth](https://img.shields.io/badge/-NextAuth.js-000000?style=flat-square&logo=auth0&logoColor=white)

</td>
</tr>
</table>

<br/>

## 🚀 Featured Projects

### 💰 [AjoSave](https://github.com/Gr8vybs/Ajo-save)
**A peer-to-peer digital savings platform** inspired by traditional Nigerian *ajo/esusu* community savings groups — built for traders and unbanked populations in Abuja.

`Next.js 15` `NextAuth v5` `Prisma` `SQLite` `TypeScript` `Tailwind CSS`

- 📊 Trust score visualization for group members
- 🔗 Invite-code based group joining
- 💸 Contribution tracking and automated payout rotation logic

---

### 🏥 [WardLink NG](https://github.com/Gr8vybs/WardLink-NG)
**An offline-first clinical patient handoff tool** built to improve continuity of care in Nigerian hospitals, even in low-connectivity wards.

`React Native (Expo)` `NestJS` `PostgreSQL` `Redis + BullMQ` `Terraform` `Docker` `Kubernetes`

- 🔄 Offline-first sync using hybrid logical clocks and an operation log, with server-side conflict detection
- 🔐 Row-Level Security for hard multi-tenant facility isolation
- 📋 Structured handoff fields with last-write-wins + visible conflict flags, append-only notes and attachments
- 🚨 Escalation lifecycle to ward heads with a shift-boundary backstop
- 📤 Referral-as-frozen-snapshot for safe cross-facility transfers
- 🔑 Shared-device sessions with per-action PIN re-authentication
- 🛠️ Currently in active rebuild — backend scaffold live, CI green

---

### 🗄️ [DB Backup & Restore System](https://github.com/Gr8vybs/Automated-db-backup)
**A production-grade automated database backup and restore system** for PostgreSQL and MySQL — my DevOps capstone project.

`Python` `Docker` `Kubernetes` `Helm` `Terraform` `GitHub Actions`

- 🔒 AES-256-GCM encryption with zstd compression
- ☁️ Pluggable S3 and local storage backends with configurable retention policies
- 📈 Prometheus metrics and Slack/email notifications
- ⚙️ Full CI/CD pipeline with automated testing
- 🏗️ Complete infrastructure-as-code provisioning on AWS

<br/>

## 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Gr8vybs&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Gr8vybs&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gr8vybs&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Gr8vybs&theme=tokyo-night&hide_border=true" width="100%"/>
</div>

<br/>

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/Gr8vybs/Gr8vybs/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake animation" />
</div>

<br/>

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/simon-afolayan)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:simonafolayan04@gmail.com)

<br/>
<sub>Thanks for stopping by — always open to conversations about fintech, healthtech, and infrastructure that actually holds up in production.</sub>

</div>
