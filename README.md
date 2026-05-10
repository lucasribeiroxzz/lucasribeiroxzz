<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=A960FF&height=120&section=header" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=A960FF&center=true&vCenter=true&width=435&lines=Ol%C3%A1%2C+eu+sou+Lucas+Ribeiro+%F0%9F%91%8B;Desenvolvedor+Full+Stack;Estudante+de+ADS)](https://git.io/typing-svg)

<br>

[![](https://komarev.com/ghpvc/?username=lucasribeiroxzz&label=Visitantes&color=A960FF&style=flat-square)](https://github.com/lucasribeiroxzz)

</div>

## 🧑‍💻 Sobre mim

```yaml
nome: Lucas Ribeiro
localização: Brasil 🇧🇷
formação: Análise e Desenvolvimento de Sistemas (ADS)
foco: Desenvolvimento Full Stack
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

**Linguagens**

<img src="https://skillicons.dev/icons?i=python,javascript,java,lua,html,css&theme=dark" />

**Ferramentas & Tecnologias**

<img src="https://skillicons.dev/icons?i=vscode,git,github,mysql,nodejs,npm&theme=dark" />

**Estudando**

<img src="https://skillicons.dev/icons?i=react,typescript,docker,linux&theme=dark" />

</div>

---

## 📊 GitHub Stats

<div align="center">
  <a href="https://github.com/lucasribeiroxzz">
    <img height="170" src="https://github-readme-stats.vercel.app/api?username=lucasribeiroxzz&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A960FF&icon_color=A960FF&text_color=c9d1d9&include_all_commits=true&count_private=true" />
  </a>
  <a href="https://github.com/lucasribeiroxzz">
    <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucasribeiroxzz&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A960FF&text_color=c9d1d9&langs_count=6" />
  </a>
</div>

<br>

<div align="center">
  <a href="https://github.com/lucasribeiroxzz">
    <img src="https://streak-stats.demolab.com?user=lucasribeiroxzz&theme=tokyonight&hide_border=true&background=0D1117&stroke=A960FF&ring=A960FF&fire=FF6B6B&currStreakLabel=A960FF&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=555555" />
  </a>
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

> ⚠️ **Para ativar a cobra**, veja o [guia de setup](#-como-ativar-a-animação-da-cobra) no final.

---

## 📫 Conecte-se comigo

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasribeiroxzz)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/lucas.ribeiroxzz)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lucasribeiroxzz)

</div>

---

<div align="center">

### 💡 *"O código é poesia escrita em lógica."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=A960FF&height=120&section=footer" />

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
