### Olá eu sou o Lucas Rodrigues 👋🏻
<p id="typing-text"></p>

[![Portfolio](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://portfolio-lucashapr.vercel.app) <!--[![Linkedin]
(https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-henrique-b72567259/)-->
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg" href="(https://www.linkedin.com/in/lucas-henrique-b72567259/" style="width: 30px"/>

<div style="display: flex">
  <img src="https://github-readme-stats.vercel.app/api?username=LucasHapr&show_icons=true&theme=tokyonight" alt="Lucas GitHub stats" height="220">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LucasHapr&size_weight=0.3&count_weight=0.3&theme=tokyonight" alt="Top Langs" height="220">
  
</div>


## Tecnologias que eu utilizo

<div style="display: inline block">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" style="width: 40px"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" style="width: 40px"/>
</div>
<br>
Sou estudante de Engenharia de Software, com ensino médio integrado ao técnico de Desenvolvimento de Sistemas, 
com grande interesse por programação, gosto bastante de estudar e desenvolver projetos.


<script>
  const text = "Hello World, i am Lucas";
  const typingSpeed = 100;

  function typeWriter(text, i) {
    if (i < text.length) {
      document.getElementById("typing-text").innerHTML += text.charAt(i);
      i++;
      setTimeout(function() {
        typeWriter(text, i);
      }, typingSpeed);
    }
  }

  document.addEventListener("DOMContentLoaded", function() {
    typeWriter(text, 0);
  });
</script>

<style>
  #typing-text {
    color: #333;
    font-size: 24px;
    font-family: Arial, sans-serif;
    border-right: 2px solid #333;
    white-space: nowrap;
    overflow: hidden;
    width: 11em;
    animation: typing 4s steps(44, end), blink-caret 0.75s step-end infinite;
  }

  @keyframes blink-caret {
    from, to {
      border-color: transparent;
    }
    50% {
      border-color: #333;
    }
  }
</style>
