<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Resume - Full-Stack Developer</title>
<!-- Google Fonts for a modern look -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" />
<style>
  /* Reset and base styles */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: 'Inter', sans-serif;
    background-color: #0f0f0f;
    color: #eee;
    line-height: 1.6;
    padding: 20px;
    max-width: 1000px;
    margin: auto;
    /* Light glow effect on sides */
    box-shadow: inset 0 0 50px rgba(0, 255, 255, 0.2),
                inset 0 0 50px rgba(255, 0, 255, 0.2),
                0 0 30px rgba(0, 255, 255, 0.1);
    border-radius: 10px;
  }

  h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
    color: #00ffff;
    text-align: center;
    letter-spacing: 2px;
    animation: fadeInDown 1s ease-out;
  }

  h2 {
    font-size: 1.8em;
    margin-top: 40px;
    margin-bottom: 15px;
    color: #ff00ff;
    border-bottom: 2px solid #ff00ff;
    display: inline-block;
    padding-bottom: 5px;
    position: relative;
    animation: fadeInLeft 1s ease-out;
  }

  section {
    margin-bottom: 40px;
    padding: 20px;
    background-color: #1a1a1a;
    border-radius: 12px;
    box-shadow: 0 0 15px rgba(0,255,255,0.2);
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 1s forwards;
  }

  /* Sequential animation delays for each section */
  section:nth-of-type(1) { animation-delay: 0.2s; }
  section:nth-of-type(2) { animation-delay: 0.4s; }
  section:nth-of-type(3) { animation-delay: 0.6s; }
  section:nth-of-type(4) { animation-delay: 0.8s; }

  /* Headings */
  h2 {
    margin-bottom: 10px;
  }

  /* Lists */
  ul {
    list-style-type: disc;
    padding-left: 20px;
  }

  li {
    margin-bottom: 8px;
  }

  /* Projects */
  .project {
    margin-bottom: 20px;
    padding-left: 10px;
    border-left: 4px solid #00ffff;
    transition: transform 0.3s, background-color 0.3s, box-shadow 0.3s;
  }

  .project:hover {
    background-color: #333;
    transform: translateX(5px);
    box-shadow: 0 0 10px #00ffff;
  }

  .project h3 {
    font-size: 1.4em;
    margin-bottom: 8px;
    color: #ff00ff;
  }

  /* Animations */
  @keyframes fadeInDown {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  @keyframes fadeInLeft {
    from { opacity: 0; transform: translateX(-20px); }
    to { opacity: 1; transform: translateX(0); }
  }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* Responsive styles */
  @media(max-width: 600px) {
    body {
      padding: 10px;
    }
    h1 {
      font-size: 2em;
    }
    h2 {
      font-size: 1.5em;
    }
    .project h3 {
      font-size: 1.2em;
    }
  }
</style>
</head>
<body>

<h1>Resume - Full-Stack Developer</h1>

<section>
  <h2>Personal Details</h2>
  <p><strong>Name:</strong> @hiroshi@</p>
  <p><strong>Email:</strong> hiroshi@example.com</p>
  <p><strong>Phone:</strong> +49 123 4567890</p>
  <p><strong>LinkedIn:</strong> linkedin.com/in/hiroshi</p>
  <p><strong>GitHub:</strong> github.com/hiroshi</p>
  <p><strong>Location:</strong> Berlin, Germany</p>
</section>

<section>
  <h2>Professional Summary</h2>
  <p>Motivated full-stack developer with over 5 years of experience building scalable web applications. Skilled in both front-end and back-end technologies, with a focus on user-friendly solutions and teamwork.</p>
</section>

<section>
  <h2>Technical Skills</h2>
  <ul>
    <li>Front-end: HTML5, CSS3, JavaScript, React.js, Angular, Vue.js</li>
    <li>Back-end: Node.js, Express.js, Django, Ruby on Rails</li>
    <li>Databases: MySQL, PostgreSQL, MongoDB</li>
    <li>Tools & Platforms: Docker, Kubernetes, AWS, Git, Jenkins</li>
    <li>Others: REST APIs, GraphQL, WebSocket, Agile/Scrum</li>
  </ul>
</section>

<section>
  <h2>Projects</h2>
  <div class="project">
    <h3>E-Commerce Platform</h3>
    <p>Developed a full-featured online store with React, Node.js, and MongoDB, including real-time notifications and payment integration.</p>
  </div>
  <div class="project">
    <h3>Chat Application</h3>
    <p>Built a real-time chat app using WebSocket and Node.js, with user authentication and message history.</p>
  </div>
</section>

<!-- You can add more sections like Experience, Education, etc. -->

</body>
</html>
