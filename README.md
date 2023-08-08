


# Olá, meu nome é Carla
#Sou desenvolvedora Front-End, sempre em busca de novos desafios e aprendizados!

<div align="center">

</div>
  
  
<div style="display: inline_block"><br>
  <img align="center" alt="carla-js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="carla-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="carla-React" height="30" width="40" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/260px-PHP-logo.svg.png">
  <img align="center" alt="carla-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="carla-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="carla-CSS" height="30" width="40" src="https://getbootstrap.com.br/docs/4.1/assets/brand/bootstrap-social-logo.png">
  <img align="center" alt="carla-Sass" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg">
  <img align="center" alt="carla-Wordpress" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/wordpress/wordpress-original.svg">
 </div>
  

<div style="display: inline_block"><br>
  <a href = "mailto:carla.monalisa.galdino@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/carla-galdino-602976159/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 
</div>

<div>

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
</div>
