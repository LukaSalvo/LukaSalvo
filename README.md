<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Luka Salvo | Accueil</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      margin: 0;
      padding: 20px;
    }
    h1, h2, h3 {
      color: #58a6ff;
    }
    .lang-switch {
      position: absolute;
      top: 20px;
      right: 20px;
    }
    button {
      background-color: #238636;
      border: none;
      color: white;
      padding: 10px 15px;
      font-size: 14px;
      cursor: pointer;
      border-radius: 6px;
    }
    section {
      margin-bottom: 30px;
    }
    .center {
      text-align: center;
    }
    img {
      max-width: 100%;
    }
  </style>
</head>
<body>

  <div class="lang-switch">
    <button onclick="switchLang()">English</button>
  </div>

  <div id="fr">
    <h1>👋 Salut, je suis Luka !</h1>
    <p>🎓 Étudiant en BUT Informatique à l'IUT Nancy Charlemagne<br>
    🔒 Parcours DACS : Déploiement d'Applications Communicantes Sécurisées</p>

    <section>
      <h2>💻 Compétences techniques</h2>
      <ul>
        <li><strong>Langages :</strong> JavaScript, HTML, CSS, PHP, Java, C, Python (bases), Go (en cours d’apprentissage), VBA</li>
        <li><strong>Systèmes d’exploitation :</strong> Linux (utilisation avancée, scripting Bash), macOS, Windows</li>
        <li><strong>Autres :</strong> Développement web, sécurisation d’applications, déploiement d’applications communicantes</li>
      </ul>
    </section>

    <section>
      <h2>🛠️ En ce moment</h2>
      <ul>
        <li>J’approfondis mes connaissances</li>
        <li>Je travaille régulièrement sur des projets Linux, scripts Bash et l’administration système</li>
      </ul>
    </section>

    <h3 class="center">J'utilise</h3>
    <p class="center">
      <img src="https://skillicons.dev/icons?i=py,golang,java,html,css,js,nodejs,php,py,bash,mysql,c,latex&perline=20" />
    </p>

    <h3 class="center">Logiciels</h3>
    <p class="center">
      <img src="https://skillicons.dev/icons?i=docker,windows,vim,linux,vscode,apple,git,github,bsd,nginx,debian,ubuntu,emacs,grafana" />
    </p>

    <section>
      <h2>📊 Statistiques</h2>
      <img src="https://github-readme-stats.vercel.app/api?username=LukaSalvo&show_icons=true&hide=prs,issues&theme=dracula" alt="Stats GitHub" />
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=LukaSalvo&theme=dracula&hide_border=true" alt="Graph activité" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=LukaSalvo&theme=dracula&hide_border=true" alt="Streak GitHub" />
    </section>

    <section>
      <h2>📫 Me contacter</h2>
      <ul>
        <li><a href="https://github.com/LukaSalvo" target="_blank">Mon profil GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/luka-salvo-289b10291/" target="_blank">Mon profil LinkedIn</a></li>
      </ul>
    </section>

    <p><em>Passionné d’informatique, toujours curieux d’apprendre et d’expérimenter de nouvelles technologies !</em></p>
  </div>

  <div id="en" style="display:none;">
    <h1>👋 Hi, I'm Luka!</h1>
    <p>🎓 Student in Computer Science at IUT Nancy Charlemagne<br>
    🔒 DACS Path: Deployment of Secure Communicating Applications</p>

    <section>
      <h2>💻 Technical Skills</h2>
      <ul>
        <li><strong>Languages:</strong> JavaScript, HTML, CSS, PHP, Java, C, Python (basic), Go (learning), VBA</li>
        <li><strong>Operating Systems:</strong> Linux (advanced use, Bash scripting), macOS, Windows</li>
        <li><strong>Other:</strong> Web development, application security, deploying networked applications</li>
      </ul>
    </section>

    <section>
      <h2>🛠️ Currently Working On</h2>
      <ul>
        <li>Deepening my knowledge</li>
        <li>Regularly working on Linux projects, Bash scripts and system administration</li>
      </ul>
    </section>

    <h3 class="center">I use</h3>
    <p class="center">
      <img src="https://skillicons.dev/icons?i=py,golang,java,html,css,js,nodejs,php,py,bash,mysql,c,latex&perline=20" />
    </p>

    <h3 class="center">Tools</h3>
    <p class="center">
      <img src="https://skillicons.dev/icons?i=docker,windows,vim,linux,vscode,apple,git,github,bsd,nginx,debian,ubuntu,emacs,grafana" />
    </p>

    <section>
      <h2>📊 Statistics</h2>
      <img src="https://github-readme-stats.vercel.app/api?username=LukaSalvo&show_icons=true&hide=prs,issues&theme=dracula" alt="GitHub Stats" />
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=LukaSalvo&theme=dracula&hide_border=true" alt="Activity Graph" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=LukaSalvo&theme=dracula&hide_border=true" alt="GitHub Streak" />
    </section>

    <section>
      <h2>📫 Contact Me</h2>
      <ul>
        <li><a href="https://github.com/LukaSalvo" target="_blank">My GitHub Profile</a></li>
        <li><a href="https://www.linkedin.com/in/luka-salvo-289b10291/" target="_blank">My LinkedIn Profile</a></li>
      </ul>
    </section>

    <p><em>Passionate about computer science, always eager to learn and explore new technologies!</em></p>
  </div>

  <script>
    function switchLang() {
      const fr = document.getElementById('fr');
      const en = document.getElementById('en');
      const btn = document.querySelector('button');
      if (fr.style.display === 'none') {
        fr.style.display = 'block';
        en.style.display = 'none';
        btn.textContent = 'English';
      } else {
        fr.style.display = 'none';
        en.style.display = 'block';
        btn.textContent = 'Français';
      }
    }
  </script>
</body>
</html>
