<!-- Banner SVG with Embedded Animations -->
<svg width="100%" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a1a"/>
      <stop offset="100%" style="stop-color:#141432"/>
    </linearGradient>
    
    <!-- Neon Wave Gradient -->
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#4f46e5;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#5cbdb9;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#4f46e5;stop-opacity:0"/>
    </linearGradient>
    
    <!-- Glow Filter for Nodes -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Embedded CSS Keyframe Animations -->
    <style>
      @keyframes pulseText {
        0% { fill: #ffffff; filter: drop-shadow(0px 0px 2px rgba(92,189,185,0.4)); }
        50% { fill: #f3f4f6; filter: drop-shadow(0px 0px 10px rgba(92,189,185,0.8)); }
        100% { fill: #ffffff; filter: drop-shadow(0px 0px 2px rgba(92,189,185,0.4)); }
      }
      @keyframes floatWave1 {
        0% { transform: translateX(0px) translateY(0px); }
        50% { transform: translateX(20px) translateY(-4px); }
        100% { transform: translateX(0px) translateY(0px); }
      }
      @keyframes floatWave2 {
        0% { transform: translateX(0px) translateY(0px); }
        50% { transform: translateX(-15px) translateY(5px); }
        100% { transform: translateX(0px) translateY(0px); }
      }
      @keyframes starBreathe {
        0%, 100% { opacity: 0.3; r: 3px; }
        50% { opacity: 1; r: 5.5px; }
      }
      @keyframes starBreatheAlternate {
        0%, 100% { opacity: 0.8; r: 5px; }
        50% { opacity: 0.3; r: 3px; }
      }
      
      .animated-name {
        animation: pulseText 4s ease-in-out infinite;
      }
      .wave-1 {
        animation: floatWave1 8s ease-in-out infinite;
        transform-origin: center;
      }
      .wave-2 {
        animation: floatWave2 10s ease-in-out infinite;
        transform-origin: center;
      }
      .star-fast {
        animation: starBreathe 3s ease-in-out infinite;
      }
      .star-slow {
        animation: starBreatheAlternate 4s ease-in-out infinite;
      }
    </style>
  </defs>

  <!-- Background Canvas -->
  <rect width="1200" height="180" fill="url(#bgGrad)" rx="16"/>
  
  <!-- Animated Vector Waves -->
  <path class="wave-1" d="M -50 90 Q 250 30, 550 90 T 1150 90" stroke="url(#lineGrad)" stroke-width="2" fill="none" opacity="0.7"/>
  <path class="wave-2" d="M 50 120 Q 350 60, 650 120 T 1250 120" stroke="url(#lineGrad)" stroke-width="1" fill="none" opacity="0.4"/>
  <path class="wave-1" d="M -20 60 Q 280 120, 580 60 T 1180 60" stroke="url(#lineGrad)" stroke-width="1.5" fill="none" opacity="0.3"/>
  
  <!-- Interactive Ambient Nodes -->
  <circle class="star-fast" cx="150" cy="70" r="4" fill="#5cbdb9" filter="url(#glow)"/>
  <circle class="star-slow" cx="450" cy="110" r="5" fill="#4f46e5" filter="url(#glow)"/>
  <circle class="star-fast" cx="850" cy="65" r="3" fill="#5cbdb9" filter="url(#glow)"/>
  <circle class="star-slow" cx="1080" cy="115" r="4" fill="#4f46e5" filter="url(#glow)"/>
  
  <!-- Typography Layer -->
  <text class="animated-name" x="600" y="85" font-family="'Segoe UI', system-ui, sans-serif" font-size="44" font-weight="900" fill="#ffffff" text-anchor="middle" letter-spacing="4">AARYA JAGDALE</text>
  <text x="600" y="122" font-family="'Segoe UI', system-ui, sans-serif" font-size="13" font-weight="600" fill="#a5b4fc" text-anchor="middle" letter-spacing="5" opacity="0.9">COMPUTER SCIENCE • AIML • MUMBAI</text>
</svg>

<br><br>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=5CBDB9&center=true&vCenter=true&width=800&lines=Building+intelligent+systems+one+line+at+a+time;Specializing+in+CSE+(AIML)+%26+UI%2FUX;Frontend+Development+%26+Smart+Solutions" alt="Typing SVG" />
</p>

<br>

<h2 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Technologist.png" width="32"/> About Me
</h2>

<p align="center">
  <samp>
    🎓 <b>SVKM's Shri Bhagubai Mafatlal Polytechnic & College of Engineering</b>, Mumbai<br>
    💻 Engineering Student — <b>Artificial Intelligence & Machine Learning</b><br>
    🎨 Passionate about <b>Frontend UI/UX, Branding, and Creative Visual Design</b><br>
    🏐 Volleyball player driven by team collaboration, strategic layout design, and problem-solving
  </samp>
</p>

<br>

<!-- Featured Project Section for Visual Appeal -->
<h2 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" width="28"/> Featured Innovation
</h2>

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/Project-Nagar_Seva-5cbdb9?style=for-the-badge&labelColor=0a0a1a&logo=github" alt="Nagar Seva Project"/>
  </a>
</p>
<p align="center">
  <samp>
    Developed <b>Nagar Seva</b> — a gamified, smart road monitoring platform utilizing live GPS tracking<br> 
    to seamlessly detect, log, and report infrastructure issues like potholes.
  </samp>
</p>

<br>

<h2 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="28"/> Core Tech Stack
</h2>

<table align="center">
  <tr>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="45" height="45" alt="Python"/><br>
      <sub><b>Python</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="45" height="45" alt="TensorFlow"/><br>
      <sub><b>TensorFlow</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="45" height="45" alt="PyTorch"/><br>
      <sub><b>PyTorch</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="45" height="45" alt="NumPy"/><br>
      <sub><b>NumPy</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="45" height="45" alt="Pandas"/><br>
      <sub><b>Pandas</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="45" height="45" alt="JavaScript"/><br>
      <sub><b>JavaScript</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="45" height="45" alt="React"/><br>
      <sub><b>React</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="45" height="45" alt="Node.js"/><br>
      <sub><b>Node.js</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="45" height="45" alt="C++"/><br>
      <sub><b>C++</b></sub>
    </td>
    <td align="center" width="110">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="45" height="45" alt="Git"/><br>
      <sub><b>Git</b></sub>
    </td>
  </tr>
</table>

<br><br>

<p align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="12"/>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="12"/>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="12"/>
  <br><br>
  <samp><i>"The best way to predict the future is to design it."</i></samp>
  <br><br>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="12"/>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="12"/>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="12"/>
</p>
