<html>
<head>
  <title>My Portfolio</title>
  <style>
    /* Add some style to your page */
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    .header {
      display: flex;
      align-items: center;
    }
    .photo {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
    }
    .name {
      font-size: 36px;
      font-weight: bold;
      margin-left: 20px;
    }
    .bio {
      margin-top: 20px;
      font-size: 18px;
      line-height: 1.5;
    }
    .contact {
      margin-top: 20px;
      display: flex;
      gap: 10px;
    }
    .contact a {
      display: inline-block;
      width: 32px;
      height: 32px;
      background-repeat: no-repeat;
      background-size: contain;
    }
    .contact a.github {
      background-image: url("https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png");
    }
    .contact a.linkedin {
      background-image: url("https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png");
    }
    .contact a.email {
      background-image: url("https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg");
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <!-- Replace the image source with your own photo URL -->
      <img src="https://i.imgur.com/4N1DZQF.jpg" alt="My photo" class="photo">
      <!-- Replace the text with your own name -->
      <div class="name">John Doe</div>
    </div>
    <div class="bio">
      <!-- Write a short introduction about yourself -->
      <p>Hello, I'm John Doe, a web developer and designer based in Brazil. I have over 5 years of experience in creating responsive and user-friendly websites using HTML, CSS, and JavaScript. I'm passionate about learning new technologies and solving problems with creative solutions.</p>
      <!-- List some of your skills or achievements -->
      <p>Some of my skills and achievements include:</p>
      <ul>
        <li>Creating a portfolio website with GitHub Pages</li>
        <li>Winning the first prize in a hackathon</li>
        <li>Building a Chrome extension for watching Hulu shows with friends</li>
      </ul>
    </div>
    <div class="contact">
      <!-- Add links to your GitHub, LinkedIn, and email accounts -->
      <a href="https://github.com/johndoe" class="github"></a>
      <a href="https://www.linkedin.com/in/johndoe" class="linkedin"></a>
      <a href="mailto:johndoe@example.com" class="email"></a>
    </div>
  </div>
</body>
</html>
