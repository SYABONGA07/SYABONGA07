<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Siyabonga Madlala - Portfolio Banner</title>
<style>
  /* Reset and base styles */
  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    padding: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #0d0d0d; /* Dark background for contrast */
    font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  }

  /* The main banner container */
  .banner {
    position: relative;
    width: 100%;
    max-width: 850px; 
    height: 250px;    
    
    /* Blue gradient (Deep Navy to Vibrant Blue) */
    background: linear-gradient(90deg, #001f3f 0%, #007bff 100%);
    
    border-radius: 8px;
    overflow: hidden; /* IMPORTANT: Keeps the waves inside the banner */
    
    display: flex;
    justify-content: center;
    align-items: center;
    
    /* Blue glow shadow */
    box-shadow: 0 10px 30px rgba(0, 123, 255, 0.3);
  }

  /* Text container */
  .content {
    position: relative;
    z-index: 10; /* Keeps text above the background waves */
    text-align: center;
    color: #ffffff;
    padding: 0 20px;
    margin-bottom: 40px; /* Shifts text up slightly to make room for waves */
  }

  /* Name styling */
  .content h1 {
    margin: 0 0 12px 0;
    font-size: 3.2rem; 
    font-weight: 800;
    letter-spacing: -0.5px;
    text-shadow: 0 4px 10px rgba(0,0,0,0.4);
  }

  /* Subtitle styling */
  .content p {
    margin: 0;
    font-size: 1.15rem;
    font-weight: 600;
    letter-spacing: 0.5px;
    opacity: 0.95;
    text-shadow: 0 2px 5px rgba(0,0,0,0.4);
  }

  /* --- WAVE ANIMATION STYLES --- */
  .waves-container {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 120px; /* Height of the wave area */
    z-index: 5;
  }

  .waves {
    position: relative;
    width: 100%;
    height: 100%;
  }

  /* Animation for the moving waves */
  .parallax > use {
    animation: move-forever 25s cubic-bezier(.55,.5,.45,.5) infinite;
  }

  /* Different speeds and delays for each layer creates the 3D motion effect */
  .parallax > use:nth-child(1) {
    animation-delay: -2s;
    animation-duration: 8s;
  }
  .parallax > use:nth-child(2) {
    animation-delay: -3s;
    animation-duration: 12s;
  }
  .parallax > use:nth-child(3) {
    animation-delay: -4s;
    animation-duration: 16s;
  }
  .parallax > use:nth-child(4) {
    animation-delay: -5s;
    animation-duration: 22s;
  }

  /* The infinite translation keyframe */
  @keyframes move-forever {
    0% {
      transform: translate3d(-90px, 0, 0);
    }
    100% {
      transform: translate3d(85px, 0, 0);
    }
  }

  /* Responsive adjustments for smaller screens */
  @media (max-width: 600px) {
    .content h1 {
      font-size: 2rem;
    }
    .content p {
      font-size: 0.9rem;
    }
    .banner {
      height: 200px;
    }
  }
</style>
</head>
<body>

  <div class="banner">
    <div class="content">
      <h1>Siyabonga Madlala</h1>
      <p>ICT Student • Software Developer • Data Analytics</p>
    </div>

    <!-- Motion Waves SVG -->
    <div class="waves-container">
      <svg class="waves" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 24 150 28" preserveAspectRatio="none" shape-rendering="auto">
        <defs>
          <path id="gentle-wave" d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z" />
        </defs>
        <g class="parallax">
          <!-- Layered waves with varying opacities -->
          <use xlink:href="#gentle-wave" x="48" y="0" fill="rgba(255, 255, 255, 0.15)" />
          <use xlink:href="#gentle-wave" x="48" y="3" fill="rgba(255, 255, 255, 0.3)" />
          <use xlink:href="#gentle-wave" x="48" y="5" fill="rgba(255, 255, 255, 0.5)" />
          <use xlink:href="#gentle-wave" x="48" y="7" fill="rgba(255, 255, 255, 0.8)" />
        </g>
      </svg>
    </div>
  </div>

</body>
</html>

  


<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Full-Stack+Software+Developer;ASP.NET+Core+%7C+React+%7C+Next.js;Building+systems+that+actually+work.;Open+to+opportunities+%F0%9F%9A%80" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <a href="mailto:siyabongamadlala@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
<a href="https://www.linkedin.com/in/siyabonga-thobekani-madlala-335350374">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

  <a href="https://github.com/SiyabongaMadlala">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=SiyabongaMadlala&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS"/>
</div>

---

## 👋 About Me

<img align="right" width="220" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"/>

### Hey, I'm Siyabonga

I'm a **Full-Stack Software Developer** based in **DURBAN, South Africa 🇿🇦**, I am currently studying at Durban University of technology and I’m passionate about building **systems that actually work** — from healthcare platforms to e-commerce solutions.

> 💡 *"I believe software should solve real problems, not just look good on paper."*

<br/>

🟢 &nbsp;**Currently available** for freelance, intenships,contract & full-time opportunities  
📍 &nbsp;Based in Durban — open to remote work  
⚡ &nbsp;Backend-heavy, full-stack capable, always shipping

---

## 🛠️ Tech Stack

### 💻 Languages
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


### ⚙️ Frameworks & Libraries
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)


### 🗄️ Databases
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

### 🧰 Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)


---

## 📊 GitHub Stats

<div align="center">

  <!-- Overall Stats -->
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=SYABONGA07&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub Stats"/>

  <!-- Top Languages -->
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SYABONGA07&layout=compact&langs_count=6&theme=tokyonight&hide_border=true" alt="Top Languages"/>

</div>

<div align="center">

  <!-- Streak Stats -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SYABONGA07&theme=tokyonight&hide_border=true&mode=weekly" alt="GitHub Streak"/>

</div>


<div align="center">

  <!-- Streak Stats -->
  <img src="https://github-readme-stats.vercel.app/api?username=SYABONGA07&show_icons=true&theme=tokyonight" />


</div>

---

## 🎯 Currently Focused On
[████████████░░░░░░░░] System Architecture & Backend Performance

[█████████████░░░░░░░] Deployment Pipelines & Hosting Strategies  

[████████░░░░░░░░░░░░] Cloud & Production-Level Experience

[██████████████░░░░░░] Real-world Business Solutions



---

## 🤝 Let's Build Something

<div align="center">

I'm open to **freelance work**, **contract projects**,**Internships** and **full-time opportunities**.  
If you've got a problem that needs solving — let's talk.

[![Email](https://img.shields.io/badge/📧_siyabongamadlala@gmail.com-EA4335?style=for-the-badge)](mailto:siyabongamadlala@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siyabonga-thobekani-madlala-335350374)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SiyabongaMadlala)

