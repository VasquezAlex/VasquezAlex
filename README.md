<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0a0a0a&height=200&section=header&text=VasquezAlex&fontSize=56&fontColor=e0e0e0&fontAlignY=38&desc=Full%20stack%20developer%20%E2%80%A2%20self-hosted%20everything&descAlignY=60&descSize=17&descColor=a0a0a0" alt="VasquezAlex" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&size=18&duration=3500&pause=1200&color=a0a0a0&center=true&vCenter=true&width=600&lines=Vue+%2B+Node+on+the+web;Postgres+behind+every+screen;Self-hosting+with+Coolify+on+DigitalOcean;Dockerfiles+for+everything;Shipping+small%2C+checked+changes" alt="typing" />
</p>

<p align="center">
  <a href="https://devyrse.com"><img src="https://img.shields.io/badge/Devyrse-live-f2734a?style=for-the-badge" alt="Devyrse" /></a>
  <a href="https://status.devyrse.com"><img src="https://img.shields.io/badge/status-live-4cc38a?style=for-the-badge" alt="Status page" /></a>
  <img src="https://img.shields.io/badge/self--hosted-first-2a2a2a?style=for-the-badge" alt="Self-hosted first" />
</p>

<br/>

## About

I build web apps end to end: a Vue and Next.js frontend, JavaScript services on the backend, and the Postgres database, servers and deploys underneath. I also write C# and Python when a project needs them. I'd rather run things on a server I control, with Coolify on DigitalOcean, than on a managed platform, and I write the Dockerfiles myself.

<br/>

## Devyrse

I own and build [Devyrse](https://devyrse.com), a team chat app for software teams. It's one repository that holds the website, the API, the Electron desktop app, the Windows setup and the status page. Every change goes through CI before it reaches anyone.

| | |
| :--- | :--- |
| Website | [devyrse.com](https://devyrse.com) |
| Changelog | [devyrse.com/changelog](https://devyrse.com/changelog) |
| Status | [status.devyrse.com](https://status.devyrse.com) |

**How it's put together**

- **Website:** Vue 3 and Vite.
- **API:** Hono on Node, with Drizzle over Postgres on Neon.
- **Desktop:** an Electron app that updates itself.
- **Status page:** a Cloudflare Worker that checks the site, the API and downloads every minute, and emails me when something goes down.
- **Checks:** CI runs lint, tests, gitleaks, Semgrep and k6 load tests on every pull request.

<br/>

## Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/Vue-3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white" alt="Hono" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
</p>

<br/>

## Infrastructure

| Area | What I use |
| :--- | :--- |
| Servers | A DigitalOcean droplet running Coolify, which builds the Docker images from each repo |
| Database | Postgres on Neon, with a production branch and a staging branch |
| Edge | Cloudflare for DNS, the status Worker and object storage for downloads |
| Email | Resend, for sign-up and reset mail |
| Releases | GitHub Actions: a ship from `main` deploys production, and the desktop app goes out as a versioned release |

The operating notes live in the Devyrse repository, next to the code they describe.

<br/>

## Currently working on

- Devyrse: a team chat app, with a status page that reports real API response times
- Keeping deploys small and checked, so a release is never a surprise
- Writing Dockerfiles that build the same way on every machine

<br/>

## GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=VasquezAlex&show_icons=true&theme=graywhite&hide_border=true&border_radius=6&bg_color=0a0a0a&title_color=e0e0e0&text_color=a0a0a0&icon_color=808080" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VasquezAlex&layout=compact&theme=graywhite&hide_border=true&border_radius=6&bg_color=0a0a0a&title_color=e0e0e0&text_color=a0a0a0" width="49%" />
</p>

<br/>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0a0a0a&height=90&section=footer&text=Thanks%20for%20stopping%20by&fontSize=16&fontColor=a0a0a0&fontAlignY=60" alt="footer" />
</p>
