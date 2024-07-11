<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#work">Work</a></li>
          <li><a href="#resume">Resume</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
      <section id="about">
        <h2>About Me</h2>
        <p>I'm the current CEO of GOMYCODE and have studied Web development</p>
      </section>
      <section id="work">
        <h2>My Work</h2>
        <ul>
          <li>Project 1 : CEO of GOMYCODE</li>
          <li>Project 2 : A project manager</li>
          <li>Project 3 : Web designer </li>
        </ul>
      </section>
      <section id="resume">
        <h2>My Resume</h2>
          <li>Name : Taha Yazidi</li>
          <li>Email : tahayazidi20058xyz@gmail.com</li>
          <li>My resume : Im Taha Yazidi , i am 21 years old , im the current Ceo of the Gomycode buisnes .
             I have studied wed designing, communication and computer science for 5 years and i have worked 
             as a web designer and project manager for 4 years before becauming who i am today .</li>
      </section>

      <section id="contact">
        <h2>Contact Me</h2>
        <form action="/submit-contact" method="POST">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required><br><br>
          
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required><br><br>
          
          <label for="message">Message:</label><br>
          <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
          
          <button type="submit">Send Message</button>
        </form>
      </section>
      <video controls>
        <source src=https://youtu.be/IXqySuJ7nN4?sipUujYvS4yBKGVm9Y type="video/mp4">
      <p>&copy; Fama Menou Podcast with Yahya Bouhlel #26 | GoMyCode.</p>
      </video>
        <p>&copy; 2024 Taha Yazidi. All rights reserved.</p>
      </footer>
      
      

</body>
</html>
