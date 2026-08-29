<!-- ============ HEADER BANNER ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=250&section=header&text=Pritam%20Patra&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=32&desc=Full-Stack%20%26%20AI%20Engineer%20|%20Building%20Autonomous%20Systems&descAlignY=52&descSize=18" width="100%"/>

<a href="https://pritam-ochre.vercel.app">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=90&lines=Turning+ideas+into+shipped+products+%E2%9A%A1;3rd+Year+B.Tech+CSE+%40+GNIT+%7C+CGPA+8.90;Building+Scalable+Web+%2B+Autonomous+AI+Agents+%F0%9F%A4%96;Open+For+Work+%F0%9F%9F%A2" alt="Typing SVG"/>
</a>

<br/><br/>

<a href="https://pritam-ochre.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/pritam-patra-453996327/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:your-patrapritam567@gmail.com.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>


<br/><br/>

<!-- LIVE GITHUB BADGES -->
![GitHub followers](https://img.shields.io/github/followers/Pritam-mb?style=for-the-badge&color=8B5CF6&labelColor=1a1a2e)
![GitHub User's stars](https://img.shields.io/github/stars/Pritam-mb?style=for-the-badge&color=8B5CF6&labelColor=1a1a2e)
![Public Repos](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/users/Pritam-mb&label=Repos&query=public_repos&style=for-the-badge&color=8B5CF6&labelColor=1a1a2e)
![Profile views](https://komarev.com/ghpvc/?username=Pritam-mb&color=8B5CF6&style=for-the-badge&label=PROFILE+VIEWS)

</div>

<br/>

<!-- ============ ABOUT (with coding gif) ============ -->
<table>
<tr>
<td width="60%" valign="top">

### 🧠 About Me

```yaml
name: Pritam Patra
role: Full-Stack & AI Engineer
education: "B.Tech CSE, Guru Nanak Institute of Technology (2024–Present) | CGPA: 8.90"
focus: [Scalable Web Architectures, Autonomous AI Agents, Computer Vision, GenAI]
status: "🟢 Open For Work"
fun_fact: "I ship faster than my coffee gets cold ☕"

I'm a third-year CSE student passionate about building highly scalable web architectures and integrating autonomous AI agents to solve real-world problems. Currently juggling hackathons, RAG pipelines, and computer vision models — sometimes all in the same week.


⚙️ Technical Arsenal


📊 GitHub Analytics


🏆 Trophy Cabinet


🛠️ Featured Builds
🔬 Vulcan Shield CV pipeline for microscopic PCB defect detection — improved manufacturing QC precision. Computer Vision PyTorch

🏥 Aarogya Sahayak — Best Innovative Idea 24/7 multilingual RAG healthcare assistant with auto hospital-locate & bed booking. FastAPI RAG GenAI

🌍 Geo-Space Real Estate NFT-based real estate on Celo — fractional ownership & AGT rewards. Celo Solidity React.js

✈️ Vibe Trip Travel Architect Real-time collaborative AI trip planner with dynamic itineraries. React.js Tailwind Gemini AI



🐍 Contribution Snake


💬 Let's Talk.
Whether it's scalable backend systems or your next hackathon idea — my inbox is open.


```
Setting this up on your GitHub — step by step:

The trick with this style of README is that it isn't attached to a regular project repo; GitHub has a special feature where if you create a repository with the exact same name as your username, whatever README.md is in that repo gets automatically pinned to the top of your profile page. Since your account is Pritam-mb, you need to create a new repository literally named Pritam-mb.

Start by going to github.com/new while logged into your Pritam-mb account, and in the "Repository name" field type exactly Pritam-mb (case-sensitive match with your username matters). GitHub will actually show you a little message confirming "This is a special repository" once you type the matching name, which tells you it's recognized correctly. Make sure to set it to Public and check the box to initialize it with a README, then create the repository.

Once the repo exists, open the README.md file inside it, click the pencil/edit icon, delete whatever placeholder content is there, and paste in the full markdown block above. Before committing, go through and swap out the placeholders: replace your-linkedin-handle, your-email@example.com, and your-twitter-handle with your actual handles. The Pritam-mb username is already correct throughout since I've hardcoded it in based on your real account. Commit the changes directly to the main branch, and within a few seconds your profile page at github.com/Pritam-mb should refresh and show the full animated README.

For the animated snake graph specifically, that image won't render until you add one more file: an automation script that generates it daily. In the same Pritam-mb repository, create a new file at the path .github/workflows/snake.yml and paste this in:

Copyname: Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [main]

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Pritam-mb
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
