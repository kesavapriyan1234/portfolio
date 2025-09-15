<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>K.KESAVA PRIYAN| Portfolio</title>
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: #f9f9f9; color: #333;}
    a {text-decoration: none; color: inherit;}
    
    /* Navbar */
    nav {
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      background: #2c3e50;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      z-index: 1000;
    }
    nav h1 {color: #fff; font-size: 1.5em;}
    nav ul {list-style: none; display: flex;}
    nav ul li {margin: 0 15px;}
    nav ul li a {color: #fff; font-weight: 500; transition: 0.3s;}
    nav ul li a:hover {color: #1abc9c;}
    
    /* Header */
    header {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
                  url('https://source.unsplash.com/1600x900/?technology,computer') no-repeat center/cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      padding: 20px;
    }
    header h2 {font-size: 2.5em;}
    header p {font-size: 1.2em; margin-top: 10px;}
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      background: #1abc9c;
      color: white;
      border-radius: 5px;
      transition: 0.3s;
    }
    .btn:hover {background: #16a085;}
    
    /* Sections */
    section {
      max-width: 1000px;
      margin: 80px auto;
      padding: 40px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    section h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #2c3e50;
      font-size: 2em;
    }
    
    /* Skills */
    .skills {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .skill {
      background: #1abc9c;
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.3s;
    }
    .skill:hover {background: #16a085;}
    
    /* Contact */
    .contact-info p {margin: 10px 0; font-size: 1.1em;}
    footer {
      text-align: center;
      background: #2c3e50;
      color: white;
      padding: 20px;
      margin-top: 40px;
    }

    /* Smooth scroll */
    html {scroll-behavior: smooth;}
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <h1>K. Kesava Priyan</h1>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="#sample">sample</a></li>

    </ul>
  </nav>

  <!-- Header -->
  <header>
    <h2>Hello, I'm <span style="color:#1abc9c;">Kesava priyan</span></h2>
    <p>Student | second your B.C.A</p>
    <a href="#contact" class="btn">Get in Touch</a>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p style="text-align:center;">I am <b>K. Kesavapriyan</b>, a passionate second-year BCA student. 
      I enjoy solving problems using programming languages and developing efficient software solutions. 
      My career goal is to grow as a skilled software developer while continuously learning new technologies.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill">Python</div>
      <div class="skill">Java</div>
      <div class="skill">Type Writing</div>
      <div class="skill">Web Development</div>
       <div class="skill">C++</div>
    </div>
  </section>

  <section id="education">
    <h2>Education</h2>
    <table style="width:100%; border-collapse: collapse; text-align:center; font-size:1.1em;">
      <tr style="background:#1abc9c; color:white;">
        <th style="padding:12px; border:1px solid #ddd;">Qualification</th>
        <th style="padding:12px; border:1px solid #ddd;">Institution</th>
        <th style="padding:12px; border:1px solid #ddd;">Year</th>
        <th style="padding:12px; border:1px solid #ddd;">Percentage / Grade</th>
      </tr>
      <tr>
        <td style="padding:10px; border:1px solid #ddd;">SSLC</td>
        <td style="padding:10px; border:1px solid #ddd;">GVR kadapakkam</td>
        <td style="padding:10px; border:1px solid #ddd;">2023</td>
        <td style="padding:10px; border:1px solid #ddd;">70%</td>
      </tr>
      <tr>
        <td style="padding:10px; border:1px solid #ddd;">HSC</td>
        <td style="padding:10px; border:1px solid #ddd;">GVR kadapakkam</td>
        <td style="padding:10px; border:1px solid #ddd;">2024</td>
        <td style="padding:10px; border:1px solid #ddd;">85%</td>
      </tr>
      <tr>
        <td style="padding:10px; border:1px solid #ddd;">B.C.A</td>
        <td style="padding:10px; border:1px solid #ddd;">Sri Malolan College of Arts and Science</td>
        <td style="padding:10px; border:1px solid #ddd;">2025</td>
        <td style="padding:10px; border:1px solid #ddd;">Pursuing</td>
      </tr>
    </table>
  </section>
  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact-info" style="text-align:center;">
      <p><b>Date of Birth:</b> [07/09/2007[index.html](https://github.com/user-attachments/files/22327417/index.html)
]</p>
      <p><b>Address:</b> [north mada street;kadukkalur village&post;cheyyur taluk;chengalpattu dis]</p>
      <p><b>Email:</b> <a href="mailto:honeyk72007@gmail.com">honeyk72007@gmail.com</a></p>
      <p><b>Mobile:</b> 9943090545</p>
    </div>
  </section>



  <footer>
    © 2025 K. kesava Priyan | Portfolio Website
  </footer>

</body>
</html>

