# Welcome to My GitHub! 👋

### **Pratik Bhandurge**  
**Expert Full-Stack Developer** | **Leveraging Modern Tech for Robust Web Apps** | **MVC & Oracle Pro**

---

🌐 **Driven to Develop!**  
Crafting innovative web applications that empower businesses, I bring 2.6+ years of expertise in full-stack software development. My skills focus on delivering robust solutions using **.NET**, **Angular**, and **AWS**. Whether you're here to explore my projects or looking for collaboration, welcome aboard! Let's build something extraordinary. 🚀

---

### **About Me**
- 🔭 **Current Role:** Software Developer @ **ICICI Lombard** (Dec 2022 - Present | Hybrid)  
- 💼 **Experience:** 2.6+ years in enterprise-grade, scalable web application development.  
- ⚙️ **Tech Stack:** Full-stack development with a focus on **.NET Core**, **Angular**, **AWS**, and **MVC architecture**.  
- 🌱 **Learning:** Diving deeper into **Angular advancements** and **cloud-native solutions**.  
- 🎯 **Focus Areas:** Delivering streamlined, user-friendly solutions to enhance business operations.  
- 💡 **Motto:** Build smart. Build scalable.

---

### **GitHub Stats**
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Pratikbhandurge2022&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Pratikbhandurge2022&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="Top Languages" />
</div>

---

### **Snake Animation**
<p align="center">
  <img src="https://raw.githubusercontent.com/Pratikbhandurge2022/Pratikbhandurge2022/output/snake.svg" alt="Snake animation" />
</p>

#### **Snake Animation Workflow**
```yaml
name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

---

### **Connect With Me**
<div align="left">
  <a href="https://www.linkedin.com/in/pratikbhandurge2022"><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="LinkedIn" /></a>
  <a href="https://twitter.com/yourtwitterhandle"><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="52" height="40" alt="Twitter" /></a>
  <a href="https://discord.gg/yourdiscordlink"><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="Discord" /></a>
  <a href="https://www.youtube.com/channel/yourchannelid"><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="YouTube" /></a>
</div>

---

### **Spotify: Recently Played**
<div align="center">
  <img src="https://spotify-recently-played-readme.vercel.app/api?count=5" alt="Spotify Recently Played" />
</div>

---

### **Profile Visitor Count**
<div align="center">
  <img src="https://profile-counter.glitch.me/Pratikbhandurge2022/count.svg?" alt="Visitor Count" />
</div>

---

### **Latest Blog Posts**
<div align="center">
  <img src="https://github-read-medium-git-main.pahlevikun.vercel.app/latest?limit=4" alt="Latest Blog Posts" />
</div>

---

### **Let's Collaborate!**
💬 Whether you're interested in creating cutting-edge software solutions or just exploring possibilities, feel free to connect. Together, we can drive innovative projects forward!
