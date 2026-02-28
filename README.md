## Sobre mim

# Olá pessoal, sou o Rodrigo estudo programação por hobby, mas busco aprimorar meus conhecimentos como desenvolveor front-end

<section class="skills">
<h2>Linguagens que domino</h2>


<div class="skills-grid top-row">
  <div class="skill-card">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1280px-HTML5_logo_and_wordmark.svg.png" alt=icone width="80" height="80">
    <h3>HTML</h3>
<span>Intermediario</span>
  </div>

<div class="skills-grid top-row">
  <div class="skill-card">
<h3>CSS</h3>
<img src="https://www.dialhost.com.br/blog/wp-content/uploads/2019/09/CSS_logo-1-726x1024.png" alt=icone width="65" height="65">
    <h3>CSS</h3>
<span>Intermediario</span>
  </div>

  .skills {
  text-align: center;
}

.skills-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 22px;
  margin-top: 25px;
}

.top-row {
  margin-bottom: 30px;
}

.skill-card {
  background: var(--card);
  border: 1px solid var(--border);
  padding: 20px;
  width: 160px;
  border-radius: 12px;
  transition: 0.3s ease;
  backdrop-filter: blur(8px);
}

.skill-card:hover {
  transform: translateY(-5px);
  background: rgba(255,255,255,0.12);
}
  

