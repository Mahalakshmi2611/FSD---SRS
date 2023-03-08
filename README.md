# FSD---SRS

# INTRODUCTION
A portfolio website is a unique way to showcase one’s work and let others know about them. It’s like an evergreen platform for one’s projects, case studies, and information about them. In addition, it’s one of the best ways to express personality, experience, and capabilities.

# DOCUMENT PURPOSE
The document contains the information regarding the Portfolio Management System. The SRS covers all of the requirements that are needed to complete the project. It will be the first release of the system. The purpose is to create a computerized system that will transform the whole rigorous job of creating and managing the portfolios to a trouble-free job that will be gripped in a compact and efficient manner.

# PRODUCT SCOPE
A web based system for portfolio & CV management is being proposed. It will enable the professionals from all over the world to create an online portfolio including their educational details, contact details and projects that they have worked on. The system would enable the contractors to search the professionals from our website using either the category wise distribution system, by a specific project name that they have worked on, by name, by the keywords/tags that professionals have included etc. After finding a specific professional of his need, a contractor can contact a professional either through our website or the contact details that he has provided. Currently there does not exist any website providing such functionality and we hope that the website will do a good business. It will benefit the professionals in a way that, they don’t have to develop a whole website for their portfolio; they can easily maintain an online portfolio on our website. On the other hand, it will also help the contractors as well i.e. in finding the employees easily.
# INTENDED AUDIENCE
The document is intended to be read by project managers, developers, testers, and documentation writers. The purpose of this document is to serve as a guide to designers, developers and testers who are responsible for the engineering of this project. It should give the engineers all of the information necessary to design, develop and test the software. Proceeding

# PRODUCT FUNCTIONALITY
The Portfolio Management System will be maintaining the information about the registers members of website. Following are the key functionalities that will be provided by the system

# OPERATING ENVIRONMENT 
The website will be compatible with all the major browsers like Mozilla Firefox, Google Chrome, Opera etc. and platform (Windows XP, Windows Vista and Windows 7, Linux, Macintosh etc.). This website will also be surfed on mini browsers.

# SAMPLE CODE
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Create your dream portfolio website</title>
    <!----CSS link----->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="hero">
      <nav>
        <img src="./img/tag.png" class="tag" />
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Portfolio</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Contact details</a></li>
        </ul>
        <a href="#" class="btn">Resume</a>
      </nav>

      <div class="content">
        <span class="title">Freelance Full stack Web Developer</span>
        <h1>Hello, I’m <span>emma</span></h1>
        <p>
          I’m working on a professional, visually sophisticated, Easy to use and
          technologically proficient, responsive and multi-functional React
          Components.
        </p>
        <a href="#" class="btn">Download CV</a>
      </div>
    </div>
  </body>
</html>
