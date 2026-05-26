<h1 align="center">Hey 👋<br>I am Subhadeep Adhikary</h1>

###
<div xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 500" width="100%" height="100%">
  <defs>
    <filter id="skyblueGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>

    <style>
      /* Smooth pulsing for the skyblue core ring */
      @keyframes core-pulse {
        0% { r: 84px; opacity: 0.4; }
        50% { r: 92px; opacity: 0.8; }
        100% { r: 84px; opacity: 0.4; }
      }
      
      /* Perfect 360-degree orbit loop for the outer skills */
      @keyframes slow-orbit {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
      }

      /* Counter-spin rotation to keep logos level and upright while orbiting */
      @keyframes counter-spin {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(-360deg); }
      }

      .pulse-ring { 
        animation: core-pulse 4s infinite ease-in-out; 
      }
      
      .rotating-track { 
        animation: slow-orbit 50s infinite linear; 
        transform-origin: 250px 250px; 
      }

      .skill-node { 
        animation: counter-spin 50s infinite linear; 
      }
      
      .tech-logo {
        transform: translate(-14px, -14px);
        width: 28px;
        height: 28px;
      }
    </style>
    
    <linearGradient id="darkDiskGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#020617" stop-opacity="0.9" />
      <stop offset="100%" stop-color="#0f172a" stop-opacity="0.75" />
    </linearGradient>
    <linearGradient id="coreGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#030712" stop-opacity="0.8" />
      <stop offset="100%" stop-color="#0b1329" stop-opacity="0.5" />
    </linearGradient>
  </defs>

  <circle cx="250" cy="250" r="160" fill="none" stroke="url(#darkDiskGrad)" stroke-width="70" />
  
  <circle cx="250" cy="250" r="195" fill="none" stroke="#38bdf8" stroke-width="2" filter="url(#skyblueGlow)" opacity="0.9" />
  <circle cx="250" cy="250" r="125" fill="none" stroke="#0ea5e9" stroke-width="1.5" opacity="0.5" />

  <circle class="pulse-ring" cx="250" cy="250" r="85" fill="none" stroke="#38bdf8" stroke-width="2" filter="url(#skyblueGlow)" />
  <circle cx="250" cy="250" r="80" fill="url(#coreGrad)" stroke="#38bdf8" stroke-width="2" />
  
  <text x="250" y="242" font-family="system-ui, -apple-system, sans-serif" font-weight="800" font-size="24" fill="#f5deb3" text-anchor="middle" letter-spacing="1.5" filter="drop-shadow(0px 2px 4px rgba(0,0,0,0.6))">Subhadeep</text>
  <text x="250" y="262" font-family="system-ui, -apple-system, sans-serif" font-weight="600" font-size="11" fill="#f5deb3" opacity="0.8" text-anchor="middle" letter-spacing="2.5">DEVELOPER</text>

  <g class="rotating-track">
    
    <g transform="translate(250, 90)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://skillicons.dev/icons?i=py"/>
      </g>
    </g>

    <g transform="translate(363, 137)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>
      </g>
    </g>

    <g transform="translate(410, 250)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>
      </g>
    </g>

    <g transform="translate(363, 363)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"/>
      </g>
    </g>

    <g transform="translate(250, 410)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>
      </g>
    </g>

    <g transform="translate(137, 363)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" style="filter: invert(1);"/>
      </g>
    </g>

    <g transform="translate(90, 250)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg"/>
      </g>
    </g>

    <g transform="translate(137, 137)">
      <g class="skill-node" transform-origin="0 0">
        <circle cx="0" cy="0" r="23" fill="#030712" stroke="#38bdf8" stroke-width="2" />
        <image class="tech-logo" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg"/>
      </g>
    </g>
    
  </g>
</div>

<!-- <p align="center">
  <img src="skills-disk.svg" width="460" alt="My tech Skill Disk"/>
</p> -->
<!-- <div align="center">
  <img src="https://skillicons.dev/icons?i=py" height="57" alt="python logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="57" alt="html5 logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="57" alt="css logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="57" alt="javascript logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="57" alt="java logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="57" alt="c logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="57" alt="vscode logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="57" alt="flask logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="57" alt="mysql logo"  />
  <img width="26" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="57" alt="mongodb logo"  />
</div> -->

###

<br clear="both">

<div align="center">
  <a href="https://x.com/SubhadeepA22667" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="124" height="42" alt="twitter logo"  />
  </a>
  <a href="www.linkedin.com/in/subhadeep-adhikary-40b0b9322" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="124" height="42" alt="linkedin logo"  />
  </a>
  <a href=" @subhadeep  " target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="124" height="42" alt="discord logo"  />
  </a>
</div>

###

<br clear="both">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Subhadeep-Adhikary/Subhadeep-Adhikary/pacman-output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Subhadeep-Adhikary/Subhadeep-Adhikary/pacman-output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/Subhadeep-Adhikary/Subhadeep-Adhikary/pacman-output/pacman-contribution-graph.svg">
</picture>

###

<br clear="both">

<img src="https://raw.githubusercontent.com/Subhadeep-Adhikary/Subhadeep-Adhikary/snake-output/snake.svg" alt="Snake animation" />

###

<div align="center">
  <img height="200" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/80c3dffd-c628-49d1-844e-5960a300911b/dec5a92-c7133b22-e89a-4467-8706-166bcbc679ec.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzgwYzNkZmZkLWM2MjgtNDlkMS04NDRlLTU5NjBhMzAwOTExYlwvZGVjNWE5Mi1jNzEzM2IyMi1lODlhLTQ0NjctODcwNi0xNjZiY2JjNjc5ZWMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.Ym0HwecdEfO6pvoG4SbJA1AIBEWczJiwHGd-erNVluE"  />
</div>

###
