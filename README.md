<div align="center">

<!-- COBRA QUE COME OS QUADRADINHOS VERDES -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SEU_USERNAME/SEU_USERNAME/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SEU_USERNAME/SEU_USERNAME/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/SEU_USERNAME/SEU_USERNAME/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>

</div>

<br/>

<div align="center">

<!-- ANIMAÇÃO DE DIGITAÇÃO COM NOME -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=Ol%C3%A1%2C+eu+sou+Pablo+Guilherme+%F0%9F%91%8B;Desenvolvedor+Python+%F0%9F%90%8D;Apaixonado+por+tecnologia+%F0%9F%9A%80;Sempre+aprendendo+algo+novo+%F0%9F%92%BB;Bem-vindo+ao+meu+perfil!+%F0%9F%94%A5" alt="Typing SVG" />

</div>

<br/>

---

<div align="center">

<!-- GIF PROGRAMADOR ANIME/PIXEL -->
<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="280" alt="Anime Programmer GIF"/>

</div>

---

## 👾 Sobre mim

```python
class PabloGuilherme:

    nome      = "Pablo Guilherme Araujo Cruz"
    cidade    = "Escreva aqui pra eu digitar"
    idade     = "Escreva aqui pra eu digitar"

    linguagens = [
        "Python 🐍",
    ]

    interesses = [
        "Escreva aqui pra eu digitar",
        "Escreva aqui pra eu digitar",
        "Escreva aqui pra eu digitar",
    ]

    atualmente_aprendendo = "Escreva aqui pra eu digitar"
    objetivo              = "Escreva aqui pra eu digitar"
    fun_fact              = "Escreva aqui pra eu digitar"

    def falar_oi(self):
        return "Seja bem-vindo ao meu perfil! 🚀"

eu = PabloGuilherme()
print(eu.falar_oi())
```

---

## 🛠️ Tecnologias & Ferramentas

<div align="center">

![Python](https://img.shields.io/badge/Python-0d0d0d?style=for-the-badge&logo=python&logoColor=00FF41)
![Git](https://img.shields.io/badge/Git-0d0d0d?style=for-the-badge&logo=git&logoColor=00FF41)
![GitHub](https://img.shields.io/badge/GitHub-0d0d0d?style=for-the-badge&logo=github&logoColor=00FF41)
![VS Code](https://img.shields.io/badge/VS_Code-0d0d0d?style=for-the-badge&logo=visual-studio-code&logoColor=00FF41)
![Linux](https://img.shields.io/badge/Linux-0d0d0d?style=for-the-badge&logo=linux&logoColor=00FF41)
![Terminal](https://img.shields.io/badge/Terminal-0d0d0d?style=for-the-badge&logo=gnu-bash&logoColor=00FF41)

</div>

---

## 📊 Estatísticas do GitHub

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=SEU_USERNAME&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0d0d&title_color=00FF41&icon_color=00FF41&text_color=00FF41"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USERNAME&layout=compact&langs_count=7&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=00FF41&text_color=00FF41"/>

</div>

<br/>

<div align="center">

<img src="https://streak-stats.demolab.com/?user=SEU_USERNAME&theme=dark&hide_border=true&background=0d0d0d&stroke=00FF41&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&sideLabels=00FF41&dates=00FF41&currStreakNum=00FF41&sideNums=00FF41" alt="GitHub Streak" />

</div>

---

## 🐍 Minha linguagem favorita

<div align="center">

```python
# Python — simples, poderoso e elegante 🐍

def perfil_pablo():
    habilidades = ["Lógica", "Criatividade", "Persistência"]
    linguagem   = "Python"

    for skill in habilidades:
        print(f"[+] {skill} carregada com {linguagem}!")

    print("\n>>> Sistema online. Pronto para codar. 🚀")

perfil_pablo()
```

</div>

---

## 📈 Atividade recente

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SEU_USERNAME&bg_color=0d0d0d&color=00FF41&line=00FF41&point=ffffff&area=true&hide_border=true" alt="GitHub Activity Graph"/>

</div>

---

## 📬 Onde me encontrar

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d0d0d?style=for-the-badge&logo=linkedin&logoColor=00FF41)](https://linkedin.com/in/ESCREVA_AQUI)
[![Instagram](https://img.shields.io/badge/Instagram-0d0d0d?style=for-the-badge&logo=instagram&logoColor=00FF41)](https://instagram.com/ESCREVA_AQUI)
[![Gmail](https://img.shields.io/badge/Gmail-0d0d0d?style=for-the-badge&logo=gmail&logoColor=00FF41)](mailto:ESCREVA_AQUI@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-0d0d0d?style=for-the-badge&logo=firefox&logoColor=00FF41)](https://ESCREVA_AQUI.com)

</div>

---

<!-- ============================================================ -->
<!--   WORKFLOW DA COBRA — crie este arquivo no seu repositório:  -->
<!--   .github/workflows/snake.yml                                -->
<!-- ============================================================ -->
<!--
name: Generate Snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=13&duration=4000&pause=1000&color=00FF41&center=true&vCenter=true&width=500&lines=Obrigado+por+visitar+meu+perfil!+%F0%9F%92%9A;Let%27s+code+something+amazing+%F0%9F%90%8D%F0%9F%94%A5" alt="Footer" />

<br/>

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=SEU_USERNAME.SEU_USERNAME&color=00FF41&labelColor=0d0d0d&style=flat)

</div>
