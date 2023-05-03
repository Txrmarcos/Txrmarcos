### Hi there 👋

### Bem vindo ao meu repositorio 🫶🐵

[![Linkedin](	https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcos-teixeira-37676a24a/)
[![Instagram](	https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/txr_marcos/)
[![Steam](	https://img.shields.io/badge/Steam-000000?style=for-the-badge&logo=steam&logoColor=white)](https://steamcommunity.com/profiles/76561198306121337/)


![Txrmarcos GitHub stats](https://github-readme-stats.vercel.app/api?username=Txrmarcos&show_icons=true&theme=synthwave)

## Tecnologias que utilizo

[![HTML5](	https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]('https://github.com/Txrmarcos')
[![CSS](	https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)]('https://github.com/Txrmarcos')
[![JavaScrip](	https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]('https://github.com/Txrmarcos')
[![Python](	https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)]('https://github.com/Txrmarcos')
[![React](	https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)]('https://github.com/Txrmarcos')
[![Next](	https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=fff&style=for-the-badge)]('https://github.com/Txrmarcos')

- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
