# Nicole
# 👋 ¡Hola! Soy Nicole Dayana Nieto Rivera  

🎓 Estudiante de **Ingeniería de Sistemas y Computación**  
💻 Apasionada por el **desarrollo de software**, la **optimización de procesos** y el **aprendizaje continuo**  
📍 Bogotá, Colombia  

---

## 🚀 Tecnologías y Herramientas
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" height="40"/> 
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="40" height="40"/> 
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/>
</p>

---

## 📂 Proyectos Destacados
- 📌 [Talleres de Universidad](https://github.com/nicole-nieto) → Repositorios con prácticas y ejercicios. 

---

## 📊 Estadísticas de GitHub
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nicole-nieto&show_icons=true&theme=tokyonight" alt="Stats de Nicole"/>
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nicole-nieto&layout=compact&theme=tokyonight" alt="Lenguajes más usados"/>
</p>

---

## 📫 Conéctate conmigo
- ✉️ **Email:** nicolnieto48@gmail.com  
name: Generate pacman animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate pacman-contribution-graph.svg
        uses: abozanona/pacman-contribution-graph@main
        with:
          github_user_name: ${{ github.repository_owner }}


      - name: push pacman-contribution-graph.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
- 💼 [LinkedIn](https://www.linkedin.com/) *(opcional, si tienes)*  
- 🐙 [GitHub](https://github.com/nicole-nieto)  

---

✨ *Siempre en busca de aprender, mejorar y crear soluciones con impacto.*  
