## HI! I'm Julio Gabriel👋
👋 Olá! Sou um desenvolvedor Full Stack apaixonado por tecnologia e aprendizado contínuo. Trabalho com HTML,CSS,JavaScript e React, criando interfaces modernas e funcionais.  

💡 Atualmente, estou mergulhando no mundo do Java, expandindo meus conhecimentos para o back-end e buscando me tornar cada vez mais completo na área de desenvolvimento.  

📁 Aqui no meu GitHub, você vai encontrar diversos projetos alguns simples, outros mais elaborados todos feitos com dedicação, aprendizado e vontade de evoluir.  

✨ Espero que gostem dos projetos e que eles possam inspirar, ajudar ou simplesmente mostrar um pouco da minha jornada como desenvolvedor.

### 🤖 Linguagens e Tecnologias

<img 
    align="left" 
    alt="HTML"
    title="HTML" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" 
/>
<img 
    align="left" 
    alt="CSS" 
    title="CSS"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" 
/>
<img 
    align="left" 
    alt="JavaScript" 
    title="JavaScript"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" 
/>
<img 
    align="left" 
    alt="React"
    title="React" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" 
/>
<img 
    align="left" 
    alt="Bootstrap"
    title="Bootstrap" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" 
/>
<img 
    align="left" 
    alt="Git" 
    title="Git"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
/>
<br/>
<br/>
---
### 📊 Estatísticas

<p>
  <img 
    align="left" 
    alt="GitHub Stats" 
    height="200" 
    style="padding-right: 10px;" 
    src="https://github-readme-stats.vercel.app/api?username=Julio-Gadelha&show_icons=true&theme=tokyonight&include_all_commits=true&locale=pt-br" 
  />
<img 
      align="left" 
      alt="GitHub Stats" 
      height="200" 
      src="https://github-readme-stats.vercel.app/api/top-langs/?username=Julio-Gadelha&theme=tokyonight&layout=compact&custom_title=Tecnologias&langs_count=9" 
  />

</p>

---

<div> 

name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  




