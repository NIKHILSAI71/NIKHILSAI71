<div align="center">
  <h1>
    <span class="text-gradient">Hi there, I'm NIKHILSAI71!</span>
     <span class="hand-wave">👋</span>
  </h1>
  <div class="profile-image-container">
    <img src="https://avatars.githubusercontent.com/u/119239643?v=4" alt="NIKHILSAI71 Profile Picture" class="profile-image" />
  </div>
    <p class="intro">
        A passionate developer driven by innovation and efficiency. I'm always seeking new challenges and collaborative opportunities.
    </p>
</div>

<div align="center">
  <div class="code-animation-container">
    <img src="https://user-images.githubusercontent.com/119239643/285475643-f461944e-b65e-4923-8230-f4a278c94d80.gif" alt="Coding Animation" class="code-animation"/>
  </div>
</div>

<hr class="separator" />

<div class="feature-section">
  <h2><span class="icon">🚀</span> What You'll Find Here</h2>
  <div class="feature-grid">
        <div class="feature-card">
            <h3 class="feature-title"><span class="icon">💻</span> Projects</h3>
            <p class="feature-description">Explore my diverse portfolio of web development, scripting, and open-source contributions.</p>
        </div>
        <div class="feature-card">
            <h3 class="feature-title"><span class="icon">🤝</span> Contributions</h3>
            <p class="feature-description">I'm eager to collaborate and contribute to projects that make a difference.</p>
        </div>
        <div class="feature-card">
            <h3 class="feature-title"><span class="icon">📚</span> Learning</h3>
            <p class="feature-description">Constantly refining my skills in cloud computing and cutting-edge JavaScript techniques.</p>
        </div>
    </div>
</div>

<hr class="separator" />

<div class="skills-section">
  <h2><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="20" class="skill-icon" /> Skills</h2>
  <div class="skill-grid">
      <span class="skill-badge"><code>JavaScript</code></span>
      <span class="skill-badge"><code>Python</code></span>
      <span class="skill-badge"><code>HTML</code></span>
      <span class="skill-badge"><code>CSS</code></span>
      <span class="skill-badge"><code>SQL</code></span>
      <span class="skill-badge"><code>React</code></span>
      <span class="skill-badge"><code>Node.js</code></span>
      <span class="skill-badge"><code>Express</code></span>
      <span class="skill-badge"><code>Bootstrap</code></span>
      <span class="skill-badge"><code>Pandas</code></span>
      <span class="skill-badge"><code>NumPy</code></span>
      <span class="skill-badge"><code>Git</code></span>
      <span class="skill-badge"><code>Docker</code></span>
      <span class="skill-badge"><code>AWS</code></span>
      <span class="skill-badge"><code>Linux</code></span>
      <span class="skill-badge"><code>MongoDB</code></span>
      <span class="skill-badge"><code>REST APIs</code></span>
    </div>
</div>

<hr class="separator" />

<div class="connect-section">
    <h2><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="20" class="connect-icon"/> Connect</h2>
    <div class="connect-links">
        <a href="https://www.linkedin.com/in/nikhil-sai-556866245/" target="_blank" class="connect-link">
            <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn Profile" class="connect-button"/>
        </a>
        <a href="mailto:nikhilsai.711@gmail.com" target="_blank" class="connect-link">
            <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" alt="Email" class="connect-button"/>
        </a>
    </div>
</div>

<hr class="separator" />

<div class="stats-section">
    <h2><span class="icon">📊</span> GitHub Activity</h2>
    <div class="stats-cards">
         <img src="https://github-readme-stats.vercel.app/api?username=NIKHILSAI71&show_icons=true&theme=dark" alt="Your GitHub Stats" class="stats-card" />
         <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NIKHILSAI71&layout=compact&langs_count=8&theme=dark" alt="Your Top Languages" class="stats-card"/>
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=NIKHILSAI71&theme=dark" alt="Your GitHub Streak" class="stats-card" />
     </div>
</div>


<style>

body {
    font-family: 'Arial', sans-serif;
    color: #333;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #fff;
}

.text-gradient {
    background: linear-gradient(to right, #007bff, #00b3e6);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    font-size: 2.5em;
    font-weight: bold;
}


.hand-wave {
    display: inline-block;
    animation: wave-animation 2.5s infinite;
    transform-origin: 70% 70%;
}

@keyframes wave-animation {
    0%, 100% { transform: rotate(0deg); }
    10% { transform: rotate(16deg); }
    20% { transform: rotate(-12deg); }
    30% { transform: rotate(14deg); }
    40% { transform: rotate(-6deg); }
    50% { transform: rotate(10deg); }
}

.profile-image-container {
    margin-bottom: 20px;
    display: inline-block;
    position: relative; /* For the radial effect */
}
.profile-image {
    width: 150px;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

.profile-image-container::before {
    content: "";
    position: absolute;
    top: -5px;
    left: -5px;
    right: -5px;
    bottom: -5px;
    border-radius: 50%;
    background-image: radial-gradient(circle, rgba(100, 181, 246, 0.3), transparent);
    opacity: 0;
    transition: opacity 0.4s ease;
}

.profile-image-container:hover::before {
    opacity: 1;
}

.intro {
    font-size: 1.1em;
    color: #333;
    margin-top: 20px;
    text-align: center;
}

.code-animation-container {
    text-align: center;
    margin: 20px 0;
    display: inline-block;
    overflow: hidden;
    position: relative;
}

.code-animation-container::before{
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: linear-gradient(to right, transparent 0%, white 25%, white 75%, transparent 100%);
        animation: shimmer 1.8s ease-in-out infinite;
        z-index: 1;
}

@keyframes shimmer {
        0%{
                transform: translateX(-100%);
        }
        100%{
                transform: translateX(100%);
        }
}

.code-animation {
    width: 250px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.separator {
  border: none;
  border-top: 1px solid #ddd;
  margin: 30px 0;
}

.feature-section,
.skills-section,
.connect-section,
.stats-section {
  text-align: center;
  margin-bottom: 40px;
}

.feature-section h2,
.skills-section h2,
.connect-section h2,
.stats-section h2{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
}

.icon {
  margin-right: 8px;
}

.feature-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  width: 100%;
  max-width: 800px;
  margin-top: 20px;
}

.feature-card {
    border: 1px solid #e0e0e0;
    padding: 20px;
    border-radius: 10px;
    background-color: #f9f9f9;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    flex: 1 1 250px;
    min-width: 250px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.feature-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.feature-title {
  margin-bottom: 10px;
  display: flex;
  align-items: center;
}
.feature-description {
    color: #555;
}

.skills-section h2{
    display: flex;
    align-items: center;
    justify-content: center;
}

.skill-icon{
    margin-right: 5px;
    vertical-align: middle;
}
.skill-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    margin-top: 20px;
    padding: 10px;
}
.skill-badge {
    background-color: #f0f0f0;
    padding: 5px 10px;
    border-radius: 5px;
    font-size: 0.9em;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    display: inline-block;
    margin: 5px;
}
.skill-badge:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.connect-section h2 {
    display: flex;
    align-items: center;
    justify-content: center;
}

.connect-icon{
    margin-right: 5px;
    vertical-align: middle;
}

.connect-links {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-top: 10px;
}
.connect-link {
    text-decoration: none;
}
.connect-button {
    transition: transform 0.2s ease;
}

.connect-button:hover{
    transform: scale(1.05);
}

.stats-section {
   margin-bottom: 30px;
}

.stats-section h2 {
    display: flex;
    align-items: center;
    justify-content: center;
     margin-bottom: 20px;
}
.stats-cards {
     display: flex;
     flex-wrap: wrap;
     justify-content: center;
     gap: 10px;
}

.stats-card {
    max-width: 500px;
    width: 100%;
}

</style>
