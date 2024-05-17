<!-- <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fgjbae1212%2Fhit-counter&count_bg=%23000000&title_bg=%23000000&icon=hugo.svg&icon_color=%23FFFFFF&title=Profile+Views+Hanzelkaaragac&edge_flat=false" align="right"/></a> -->
<br>
<p align="center"><img src="https://i.imgur.com/A6bWGFl.gif"/>
<img src="https://komarev.com/ghpvc/?username=hanzelkaraagac&&style=plastics&&color=yellow" align="right"/> </p>


<div align="center"> 
  <a href="https://www.youtube.com/@Berkochat/videos" target="_blank">
    <img src="https://img.shields.io/badge/-Youtube-%23333?style=for-the-badge&logo=youtube&logoColor=red" target="_blank">
  
  
  <a href="https://discord.gg/nSurjuha9E" target="_blank">
   <img alt="discord" src="https://img.shields.io/badge/Discord-%23333?style=for-the-badge&logo=discord&logoColor=#7289d9"/>
  </a>


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
