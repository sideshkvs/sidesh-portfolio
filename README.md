<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sidesh | Portfolio</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #eecdb9, #95d3ef);
      color: #1f2933;
      line-height: 1.8;
    }

    header {
      background: linear-gradient(135deg, #134e5e, #71b280);
      color: white;
      padding: 75px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 600;
    }

    header p {
      margin: 14px 0;
      font-size: 1.2rem;
    }

    nav {
      margin-top: 20px;
    }

    nav a {
      color: #e6fffa;
      margin: 0 14px;
      text-decoration: none;
      font-weight: 500;
    }

    section {
      padding: 65px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      margin-bottom: 30px;
      color: #134e5e;
      text-align: center;
      font-size: 2.2rem;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 28px;
    }

    .card {
      background: white;
      padding: 28px;
      border-radius: 16px;
      box-shadow: 0 12px 30px rgba(0,0,0,0.08);
      text-align: center;
    }

    footer {
      background: #0f172a;
      color: #cbd5e1;
      text-align: center;
      padding: 30px;
      margin-top: 60px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.3rem;
      }

      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>SIDESH KVS</h1>
    <p>Computer Science Engineer | Web Developer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#certifications">certifications</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
      
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p style="text-align:center;">
      I am a passionate and detail-oriented engineering student with a strong interest in web development and problem-solving. Currently pursuing my studies at Bannari Amman Institute of Technology, I enjoy building responsive and user-friendly websites using modern technologies. I have hands-on experience with HTML, CSS, Java, Flutter, and basic backend integration, and I continuously work on improving my technical and design skills.
    </p>
    <br>
    <p style="text-align:center;">
      I believe in learning by doing, which has led me to work on multiple academic and personal projects that focus on real-world applications and usability. I am particularly interested in creating clean UI designs combined with efficient code to deliver meaningful digital experiences. Along with technical skills, I value teamwork, adaptability, and continuous learning, and I am always eager to take on new challenges that help me grow as a developer and professional.
    </p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <p style="text-align:center;">
      <strong>B.E – Computer Science Engineering</strong><br>
      Bannari Amman Institute of Technology<br>
      2024 – 2028
    </p>
  </section>

  <section id="certifications">
    <h2>Certifications & Courses</h2>
    <div class="skills">

      <div class="card">
        <h3>Paper Presentation</h3>
        <p><strong>Pitch Craft</strong></p>
        <p>Presented innovative ideas with structured problem statements and solutions.</p>
      </div>

      <div class="card">
        <h3>Hackathon</h3>
        <p><strong>Snap AR Hackathon</strong></p>
        <p>Developed creative augmented reality experiences using Snap AR tools.</p>
      </div>

      <div class="card">
        <h3>Course Completion</h3>
        <p><strong>Python Programming</strong></p>
        <p>Covered core Python concepts, logic building, and problem solving.</p>
      </div>

      <div class="card">
        <h3>Course Completion</h3>
        <p><strong>Flutter Development</strong></p>
        <p>Learned cross-platform mobile app development using Flutter and Dart.</p>
      </div>

      <div class="card">
        <h3>Course Completion</h3>
        <p><strong>Data Science with Python</strong></p>
        <p>Learned data analysis, visualization, and basic machine learning concepts.</p>
      </div>

    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">Python</div>
      <div class="card">C</div>
      <div class="card">Flutter</div>
      <div class="card">Java</div>
    </div>
  </section>


  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">

      <div class="card">
        <h3>Buz Guide AI</h3>
        <p>Problem Faced by Rural Entrepreneurs: Starting a business in India is challenging, especially for people in villages or small towns who often struggle with registration and accessing government schemes due to lack of guidance.</p>
      </div>

      <div class="card">
        <h3>Smart Darshan Booking</h3>
        <p>The Smart Darshan Booking App is built with scalability and security in mind, ensuring safe transactions and reliable performance even during peak festival seasons. Overall, it bridges technology and tradition by making temple visits more organized, accessible, and stress-free</p>
      </div>

      <div class="card">
        <h3>Farm Smart</h3>
        <p>Farm Smart is an AI-powered app that helps Indian farmers—especially youth and smallholders—make better farming decisions with real-time, multilingual support.It provides access to crop prices, government schemes, weather alerts, expert advice, and community support, even offline</p>
      </div>

    </div>
  </section>


  <section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">Email: sideshkvs.cs24@bitsathy.ac.in</p>
    <p style="text-align:center;">GitHub: https://github.com/sideshkvs</p>
    <p style="text-align:center;">LinkedIn: www.linkedin.com/in/sidesh-kvs-029a50329</p>
    <p style="text-align:center;">Phone: 9790695276</p>
  </section>


  <footer>
    <p>© 2025 Sidesh | Built with HTML & CSS</p>
  </footer>

</body>
</html>
