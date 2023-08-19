[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+cod&weight=100&size=15&pause=1000&color=6A02F7&background=FFFDFF00&Center=true&multiline=true&repeat=false&height=90&lines=class+Python_Developer%3A;def+__init__(self%2C+name)%3A;self.name+%3D+name;Person+%3D+Python_Developer("ToshiroAkihabara"))](https://git.io/typing-svg)


![](https://komarev.com/ghpvc/?username=ToshiroAkihabara&label=OBJECTS+OF+CLASS&style=plastic&color=blueviolet)
---

- uses: Platane/snk@v3
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

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<!--
**ToshiroAkihabara/ToshiroAkihabara** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
