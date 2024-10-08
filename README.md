<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mani Chourasiya's Data Science Portfolio</title>
  <style>
    /* Body styling for dark mode with neon theme */
    body {
      background-color: #1a1a1a;
      color: #f0f0f0;
      font-family: 'Arial', sans-serif;
    }

    h1, h2 {
      color: #00FFAB; /* Neon green */
      text-align: center;
    }

    h1 img {
      vertical-align: middle;
    }

    /* Centering all content with padding */
    .content {
      padding: 20px;
      text-align: center;
    }

    /* Skill icons container */
    .skills {
      margin: 20px 0;
    }

    /* Hover effect and animations for icons */
    .skills a img {
      width: 50px;
      margin: 10px;
      transition: transform 0.5s ease, box-shadow 0.5s ease;
    }

    .skills a img:hover {
      transform: scale(1.2) rotate(10deg);
      box-shadow: 0 0 15px #00FFAB;
    }

    /* Social icons container */
    .social-icons img {
      width: 40px;
      margin: 0 15px;
      transition: transform 0.4s ease-in-out;
    }

    .social-icons img:hover {
      transform: translateY(-10px);
      filter: brightness(1.5);
    }

    /* Profile visitor count style */
    .visitor-counter {
      margin-top: 20px;
      font-size: 18px;
      color: #FFD700;
      animation: pulse 2s infinite;
    }

    /* Animation for glowing text */
    @keyframes pulse {
      0% { text-shadow: 0 0 5px #FFD700, 0 0 10px #FFD700; }
      50% { text-shadow: 0 0 20px #FFD700, 0 0 30px #FFD700; }
      100% { text-shadow: 0 0 5px #FFD700, 0 0 10px #FFD700; }
    }

    /* Section styling */
    .github-stats, .projects {
      margin: 30px 0;
    }

    /* Neon border animation for data science look */
    .github-stats img, .projects img {
      border-radius: 15px;
      border: 2px solid #00FFAB;
      transition: box-shadow 0.5s ease-in-out;
    }

    .github-stats img:hover, .projects img:hover {
      box-shadow: 0 0 25px #00FFAB;
    }
  </style>
</head>
<body>

  <!-- Introduction -->
  <div class="content">
    <h1>Hello World! I'm Mani Chourasiya <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px" height="30px"></h1>
    <p>Hi! I’m Mani Chourasiya, a final-year student currently pursuing a degree in Artificial Intelligence and Data Science. I'm passionate about AI, coding, and making the most out of every GitHub project! 💻✨</p>
  </div>

  <!-- Skill Icons with Animation -->
  <div class="skills">
    <h2>Skills</h2>
    <a href="https://github.com/mani-chourasiya?tab=repositories&q=&type=&language=python&sort=" title="Python">
      <img src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/python.svg" alt="Python">
    </a>
    <a href="https://github.com/mani-chourasiya?tab=repositories&q=&type=&language=html&sort=" title="HTML">
      <img src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/html.svg" alt="HTML">
    </a>
    <a href="https://github.com/mani-chourasiya?tab=repositories&q=&type=&language=javascript&sort=" title="JavaScript">
      <img src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/javascript.svg" alt="JavaScript">
    </a>
    <!-- Add more skill icons as needed -->
  </div>

  <!-- Social Links with Animations -->
  <div class="social-icons center">
    <a href="https://www.linkedin.com/in/mani-chourasiya-119433238">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
    </a>
    <a href="https://github.com/mani-chourasiya">
      <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub">
    </a>
    <a href="https://twitter.com/yourusername">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" alt="Twitter">
    </a>
  </div>

  <!-- GitHub Stats -->
  <div class="github-stats center">
    <h2>GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=mani-chourasiya&show_icons=true&theme=radical" alt="GitHub Stats">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=mani-chourasiya&theme=dark" alt="GitHub Streak Stats">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mani-chourasiya&layout=compact&theme=radical" alt="Top Languages">
  </div>

  <!-- Projects Section -->
  <div class="projects center">
    <h2>Recent Projects</h2>
    <img src="project_image_1.png" alt="Project 1">
    <img src="project_image_2.png" alt="Project 2">
    <!-- Add more projects as needed -->
  </div>

  <!-- Profile Visitor Counter -->
  <div class="visitor-counter center">
    <p>Profile Visitor Count: <img src="https://profile-counter.glitch.me/mani-chourasiya/count.svg" alt="Visitor Count"></p>
  </div>

</body>
</html>
