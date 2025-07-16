<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Joseph Adesewa Portfolio</title>
  <link rel="stylesheet" href="new.css" />
</head>
<body>

  <header>
    <div class="header-content">
      <h1>Joseph Adesewa Inioluwa</h1>
      <p>Virtual Assistant | Front-End Developer | Product Management Enthusiast</p>
    </div>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section class="about" id="about">
    <div class="about-content">
      <div class="about-text">
        <h2>About Me</h2>
        <p>I'm Joseph Adesewa Inioluwa, a passionate and detail-oriented Virtual Assistant and Front-End Developer with a growing background in Product Management. I currently work with Hinansho and Ayilara Sodiq as a reliable assistant, helping to streamline operations and communication. With strong skills in HTML and CSS and budding knowledge of JavaScript, I design visually appealing websites and build customized portfolios for individuals at affordable rates.
            <br><br>
            My journey started as a Computer Science student at the University of Ilorin, and I've since gained hands-on experience working with Travric as a Front-End Developer and interning at Vergold for six months. My passion for excellence, organization, and creative design shines through in everything I do.
            <br><br>
            Whether it's managing tasks, creating digital products, or coding elegant interfaces, I deliver with dedication and heart. I believe in smart, beautiful work that makes life easier—and that's what I bring to every project.
          </p>
        </div>
        <img src="your-photo.jpg" alt="Joseph Adesewa" class="profile-pic"/>
      </div>
    </section>
  
    <section class="experience" id="experience">
      <h2>Experience</h2>
      <ul><li>Virtual Assistant at Hinansho (current)</li>
        <li>Personal Assistant to Ayilara Sodiq (current)</li>
        <li>Front-End Developer at Travric Company</li>
        <li>Intern at Vergold Company (6 months)</li>
      </ul>
    </section>
  
    <section class="skills" id="skills">
      <h2>Skills</h2>
      <ul>
        <li>Virtual Assistance</li>
        <li>HTML & CSS (Strong)</li>
        <li>JavaScript (Basic)</li>
        <li>Portfolio building at affordable prices</li>
        <li>Product Management (Beginner)</li>
      </ul>
    </section>
  
    <section class="contact" id="contact">
      <h2>Contact Me</h2>
      <p>Interested in working together or getting a custom portfolio?</p>
      <a href="https://wa.me/2347025867979?text=Hi%2C%20I%E2%80%99m%20interested%20in%20Hinansho%E2%80%99s%20Services%20referred%20by%20Rahma%20My%20name%20is" class="btn">Chat on WhatsApp</a>
      <br/><br/>
      <a href="https://www.linkedin.com/in/joseph-adesewa" class="btn">View LinkedIn</a>
    </section>
  
    <footer>
      <p>© 2025 Joseph Adesewa Inioluwa</p>
    </footer>
  
  </body>
  </html>

  body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background: #f9f9f9;
  color: #333;
}

header {
    background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
  text-align: center;
  padding: 2rem 1rem;
}

header .header-content h1 {
  font-size: 2rem;
  color: #fff;
}

header .header-content p {
  color: #fff;
}


nav {
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0;
  margin: 0;
}

nav ul li {
  margin: 0 1rem;
}

nav ul li a {
  display: block;
  padding: 1rem;
  text-decoration: none;
  color: #333;
  font-weight: bold;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #ff6f61;
}


.about {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2rem;
  max-width: 1000px;
  margin: auto;
}

.about-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.about-text {
  flex: 1;
  margin-right: 20px;
}

.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #fff;
  flex-shrink: 0;
}

section {
  padding: 2rem;
  max-width: 800px;
  margin: auto;
}

section h2 {
  border-bottom: 2px solid #ccc;
  padding-bottom: 0.5rem;
  margin-bottom: 1rem;
}

ul {
  list-style-type: disc;
  padding-left: 1.5rem;
}
.btn {
    display: inline-block;
    padding: 0.8rem 1.2rem;
    margin-top: 1rem;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  
  .btn:hover {
    background-color: #0056b3;
  }
  
  footer {
    text-align: center;
    padding: 1rem;
    background: #eee;
    margin-top: 2rem;
  }
 
