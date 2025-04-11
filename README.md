<!-- Parte superior da página -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=d089ff&height=120&section=header"/>

---
## <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="28px">Hi, I'm Gabriel Cordeiro!  
### ABAP Programming Student | Full Stack Developer  

<div align="center">
  <a href="https://github.com/GabrielCordeiroBarrosoTeles">
    <!-- Uncomment this to include your GitHub Stats card -->
  <!--  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=GabrielCordeiroBarrosoTeles&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/> 
    <img height="194em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GabrielCordeiroBarrosoTeles&layout=compact&langs_count=7&theme=dark"/>-->
    <img height="199em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GabrielCordeiroBarrosoTeles&layout=compact&langs_count=20&theme=dark" alt="Github top linguagens"/>
    <img  src="https://github-readme-streak-stats.herokuapp.com/?user=GabrielCordeiroBarrosoTeles&theme=dark" alt="Github estatísticas"/>
  </a>
</div>



---

## 👥 **Nossas Equipe**

<div style="display: flex; flex-wrap: wrap; justify-content: space-around; text-align: center;">

<div style="width: 45%; margin: 10px;">
  <img src="https://avatars.githubusercontent.com/u/98492418?v=4" alt="Foto do Gabriel" style="width: 150px; height: 150px; object-fit: cover; border-radius: 50%;">
  <p><strong>Gabriel Cordeiro Barroso Teles</strong></p>
  <p>
    <a href="https://github.com/GabrielCordeiroBarrosoTeles">GitHub</a> | 
    <a href="https://www.linkedin.com/in/gabriel-cordeiro-barroso">LinkedIn</a>
  </p>
</div>

<div style="width: 45%; margin: 10px;">
  <img src="https://avatars.githubusercontent.com/u/207099894?v=4" alt="Foto do Caio" style="width: 150px; height: 150px; object-fit: cover; border-radius: 50%;">
  <p><strong>Caio Kauan Candido Cordeiro</strong></p>
  <p>
    <a href="https://github.com/CaioKauanCandidoCordeiro">GitHub</a> 
    <!-- | <a href="">LinkedIn</a>-->
  </p>
</div>

<div style="width: 45%; margin: 10px;">
  <img src="https://avatars.githubusercontent.com/u/207112570?v=4" alt="Foto do Matheus Lima" style="width: 150px; height: 150px; object-fit: cover; border-radius: 50%;">
  <p><strong>Matheus Lima</strong></p>
  <p>
    <a href="https://github.com/Eduardo-L-Silva">GitHub</a> 
    <!-- | <a href=" ">LinkedIn</a>-->
  </p>
</div>

<div style="width: 45%; margin: 10px;">
  <img src="https://avatars.githubusercontent.com/u/121130969?v=4" alt="Foto de Matheus" style="width: 150px; height: 150px; object-fit: cover; border-radius: 50%;">
  <p><strong>Esdras Cruz</strong></p>
  <p>
    <a href="https://github.com/esdrascribeiro">GitHub</a>  
    <!-- | <a href=" ">LinkedIn</a>-->
  </p>
</div>

</div>


---



<!--
Snake
<picture align="center" >
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GabrielCordeiroBarrosoTeles/GabrielCordeiroBarrosoTeles/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GabrielCordeiroBarrosoTeles/GabrielCordeiroBarrosoTeles/output/github-contribution-grid-snake-dark.svg">
  <img align="center" alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/GabrielCordeiroBarrosoTeles/GabrielCordeiroBarrosoTeles/output/github-contribution-grid-snake.svg">
</picture>
-->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GabrielCordeiroBarrosoTeles/GabrielCordeiroBarrosoTeles/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GabrielCordeiroBarrosoTeles/GabrielCordeiroBarrosoTeles/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/GabrielCordeiroBarrosoTeles/GabrielCordeiroBarrosoTeles/output/pacman-contribution-graph.svg">
</picture>

###
---

<img align="right" src="https://i.pinimg.com/originals/21/11/61/21116158daaeb1459b4ec0758505e1ad.gif" width="150" alt="Naruto hokage" />

> _"Não é a linguagem de programação que define o programador, mas sim sua lógica."_ 👨‍💻  
> — **David Ribeiro Guilherme**
<br>


---
<!-- Parte inferior da página -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=d089ff&height=120&section=footer"/>
<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->


<!--workflow snake-->
<!-- 
name: generate animation

on:
  # run automatically every 24 hours
  schedule:
    - cron: "0 */24 * * *" 
  
  # allows to manually run the job at any time
  workflow_dispatch:
  
  # run on every push on the master branch
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
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
          
          
      # push the content of <build_dir> to a branch
      # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->

<!--workflow pacman-->
<!-- 
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
-->
