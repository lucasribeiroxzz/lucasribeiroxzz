<div align="center">

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=A960FF&center=true&vCenter=true&multiline=true&repeat=true&random=false&width=600&height=100&lines=%F0%9F%91%8B+Ol%C3%A1%2C+eu+sou+Lucas+Ribeiro;Desenvolvedor+Full+Stack+%7C+Estudante+ADS" alt="Typing SVG" />
</a>

<!-- VISITOR COUNTER -->
<img src="https://komarev.com/ghpvc/?username=lucasribeiroxzz&label=Visitantes&color=A960FF&style=for-the-badge" alt="Profile views" />

</div>

---

## 🧑‍💻 Sobre mim

```yaml
nome: Lucas Ribeiro
localização: Brasil 🇧🇷
formação: Análise e Desenvolvimento de Sistemas (ADS)
foco_atual: Desenvolvimento Full Stack
aprendendo: Novas tecnologias e frameworks modernos
objetivo: Construir soluções criativas e de alto impacto
```

- 🎓 Cursando **Análise e Desenvolvimento de Sistemas (ADS)**
- 💻 Desenvolvedor com experiência em **Python**, **JavaScript** e **Java**
- 🚀 Apaixonado por tecnologia, automação e desenvolvimento de software
- 🌱 Sempre evoluindo e buscando novos desafios
- 🎮 Entusiasta de game development e scripting

---

## 🛠️ Tech Stack

<div align="center">

### Linguagens
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,javascript,java,lua,html,css&theme=dark&perline=6" alt="Languages" />
</a>

### Ferramentas & Tecnologias
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=vscode,git,github,mysql,nodejs,npm&theme=dark&perline=6" alt="Tools" />
</a>

### Estudando
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=react,typescript,docker,linux&theme=dark&perline=4" alt="Studying" />
</a>

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=lucasribeiroxzz&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A960FF&icon_color=A960FF&text_color=c9d1d9&ring_color=A960FF&include_all_commits=true&count_private=true" alt="GitHub Stats" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucasribeiroxzz&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A960FF&text_color=c9d1d9&langs_count=8" alt="Top Languages" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=lucasribeiroxzz&theme=tokyonight&hide_border=true&background=0D1117&stroke=A960FF&ring=A960FF&fire=FF6B6B&currStreakLabel=A960FF&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=555555" alt="GitHub Streak" />

</div>

---

## 🐍 Contribuições

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lucasribeiroxzz/lucasribeiroxzz/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lucasribeiroxzz/lucasribeiroxzz/output/github-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/lucasribeiroxzz/lucasribeiroxzz/output/github-snake-dark.svg" />
</picture>

</div>

> ⚠️ **Para ativar a animação da cobra**, siga o [guia de setup](#-como-ativar-a-animação-da-cobra) abaixo.

---

## 📫 Conecte-se comigo

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/SEU-LINKEDIN-AQUI)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/lucas.ribeiroxzz)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lucasribeiroxzz)

</div>

---

<div align="center">

### 💡 *"O código é poesia escrita em lógica."*

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=A960FF&height=100&section=footer" width="100%" />

</div>

---

<details>
<summary>🐍 Como ativar a animação da cobra</summary>

### Passo a passo:

1. No seu repositório `lucasribeiroxzz/lucasribeiroxzz`, vá em **Settings** → **Actions** → **General**
2. Em **Workflow permissions**, selecione **Read and write permissions** e salve
3. Crie o arquivo `.github/workflows/snake.yml` com este conteúdo:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: lucasribeiroxzz
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

4. Vá na aba **Actions** do repositório e execute manualmente o workflow **Generate Snake**
5. Pronto! A cobra vai aparecer no seu README 🎉

</details>
