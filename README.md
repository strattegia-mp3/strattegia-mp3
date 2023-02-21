<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Exemplo de Markdown com CSS</title>
  <style>
    .stats {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      grid-template-rows: repeat(2, 1fr);
      gap: 20px;
      align-items: center;
    }

    hr {
      margin: .25rem 0 .25rem 0;
    }
  </style>
</head>
<body>
<h2> Hi! I'm <b>Joisson Rocha</b></h2>

<hr />

<h3>About Me</h3> 

- I'm a student, focused on full-stack development and every day become a better person and professional.
- Acctually, I'm studying JavaScript and their frameworks.

<hr />

<!-- outro efeito -> midnight-purple | dark | dracula -->
<div align="center" class="stats">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=strattegia0704&theme=dracula"/>
  <img height="155em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=strattegia0704&layout=compact&langs_count=7&theme=dracula"/>
  <img height="140em" src="https://streak-stats.demolab.com?user=strattegia0704&theme=dracula&border=FFF&sideNums=00D081"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/wakatime?username=strattegia&theme=dracula&layout=compact"/>
</div>

<div style="display: inline_block"></div>
  
<hr /> <br />
  
<div align="center"> 
  <a href = "mailto:strattegiadev@gmail.com" target="_blank"><img src="https://img.shields.io/badge/-Gmail-C72F23?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href = "https://www.linkedin.com/in/joissonrocha/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-00669C?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>
</body>
</html>
