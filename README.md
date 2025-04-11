<!-- Parte superior da página -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=d089ff&height=120&section=header"/>

---
## <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="28px">HI, this is Team 04 of Capacita Brasil cycle 2 of the IOS Programming Track.
### Swift Developer | Mobile Programmer 



---

## 👥 **Nossa Equipe**


<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/98492418?v=4" width="150" style="border-radius: 50%"><br>
      <strong>Gabriel Cordeiro Barroso Teles</strong><br>
      <a href="https://github.com/GabrielCordeiroBarrosoTeles">GitHub</a> |
      <a href="https://www.linkedin.com/in/gabriel-cordeiro-barroso">LinkedIn</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/207099894?v=4" width="150" style="border-radius: 50%"><br>
      <strong>Caio Kauan Candido Cordeiro</strong><br>
      <a href="https://github.com/CaioKauanCandidoCordeiro">GitHub</a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/207112570?v=4" width="150" style="border-radius: 50%"><br>
      <strong>Matheus Lima</strong><br>
      <a href="https://github.com/Eduardo-L-Silva">GitHub</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/121130969?v=4" width="150" style="border-radius: 50%"><br>
      <strong>Esdras Cruz</strong><br>
      <a href="https://github.com/esdrascribeiro">GitHub</a>
    </td>
  </tr>
</table>

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
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/equipe04-ioscapacitabr/equipe04-ioscapacitabr/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/equipe04-ioscapacitabr/equipe04-ioscapacitabr/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/equipe04-ioscapacitabr/equipe04-ioscapacitabr/output/pacman-contribution-graph.svg">
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
