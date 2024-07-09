
<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=grudwald" alt="grudwald" /></a> </p>

<br>

### About me:

I started my journey in the IT industry at the age of 11 (I'm now 16) and have been tirelessly improving my skills ever since. In 5 years I have learned many languages and technologies including Python, C#, C, Bash, Lua, JavaScript and of course my favorite Golang.

Currently, I am most interested in backend development and am constantly working to expand my knowledge and practical skills in this area. I am passionate about building efficient and reliable server-side applications that keep interactive products running smoothly.

On my GitHub profile, you will find examples of my projects that demonstrate my skills with various technologies. I am always open to new learning and development opportunities, so feel free to contact me if you have interesting suggestions or ideas.

I would also like to invite you to join me on Telegram, where I share my thoughts, victories and failures: &nbsp;  [![Telegram Badge](https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/grudwald_blog)

<br><br><br>

<p align="center">
  <img width="800" height="220" src="https://streak-stats.demolab.com?user=grudwald&theme=highcontrast&hide_border=true&border_radius=5&card_width=800">
</p>

<p align="center">
  <img width="380" height="220" src="https://github-readme-stats.vercel.app/api?username=grudwald&show_icons=true&theme=vision-friendly-dark"> &nbsp;
  <img width="390" height="220" src="https://github-readme-stats.vercel.app/api/top-langs/?username=grudwald&size_weight=0.0005&count_weight=0.3&layout=compact&theme=vision-friendly-dark">
</p>



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
