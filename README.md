<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"> <!-- Include Font Awesome CSS -->
  <link rel="stylesheet" href="styles.css"> <!-- Link to external stylesheet -->
  <style>
    /* Reset default styles */

    /* Add custom font */
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap');

    /* Set up the Nord color palette */
    :root {
      --nord0: #2e3440;
      --nord1: #3b4252;
      --nord2: #434c5e;
      --nord3: #4c566a;
      --nord4: #d8dee9;
      --nord5: #e5e9f0;
      --nord6: #eceff4;
      --nord7: #D8DEE9;
      --nord8: #88c0d0;
      --nord9: #81a1c1;
      --nord10: #5e81ac;
      --nord11: #bf616a;
      --nord12: #d08770;
      --nord13: #ebcb8b;
      --nord14: #a3be8c;
      --nord15: #b48ead;
    }

    /* Body styles */
    body {
      font-family: 'Open Sans', Arial, sans-serif;
      background-color: var(--nord1);
      color: var(--nord4);
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      overflow: hidden; /* Disable scrolling */
    }

    html {
      overflow: hidden; /* Disable scrolling */
    }

    /* Container styles */
    .container {
      max-width: 600px;
      padding: 40px;
      background-color: var(--nord0);
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center; /* Center the content */
      margin: auto; /* Center horizontally */
    }

    /* Header styles */
    .header {
      margin-bottom: 20px;
    }

    .header h1 {
      font-size: 32px;
      margin-bottom: 10px;
      color: var(--nord6);
    }

    .header p {
      font-size: 16px;
      color: var(--nord4);
    }

    /* Main content styles */
    .content {
      margin-bottom: 20px;
    }

    .content p {
      line-height: 1.6;
    }

    /* Social links styles */
    .social-links {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }

    .social-links a {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 40px;
      height: 40px;
      margin: 0 10px;
      color: var(--nord4);
      background-color: var(--nord0);
      border-radius: 50%;
      text-decoration: none;
      font-size: 24px;
      transition: background-color 0.3s ease;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .social-links a:hover {
      background-color: var(--nord7);
      color: var(--nord0);
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
    }

    .social-links a i {
      pointer-events: none;
    }

    /* Footer styles */
    .footer {
      text-align: center;
      margin-top: 20px;
    }

    .footer p {
      font-size: 14px;
      color: var(--nord2);
    }

    /* Animation styles */
    @keyframes fade-in {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    /* Apply animations */
    .fade-in {
      animation: fade-in 1s ease;
    }
  </style>
</head>
<body>
  <div class="container fade-in">
    <header class="header">
      <h1>About Me</h1>
    </header>
    <div class="content">
      <p>
        hello im tron idunno why u here but this is a about me page so 
      </p>
      <p>
      <br>i like rhythm games and touhou</br>
      <br>i watch anime and</br>
      <br>i (somtimes) make music</br>
      <br>i dunno what to put in here</br> 
      <br>i dont like some stuff</br>
      <br>im always confused its normal trust me</br> 
      <br>im stupid its also normal</br> 
      <br>im 999% lazy its normal and</br> 
      <br>im bored all the time its normal :O</br>
      </p>
    </div>
    <div class="social-links">
      <a href="https://discordapp.com/channels/@me/553752561572904963/"><i class="fab fa-discord"></i></a>
      <a href="https://steamcommunity.com/id/tron12HD/"><i class="fab fa-steam"></i></a>
      <a href="https://open.spotify.com/artist/3oEXpQbY5v3gHG1xfOPPLE?si=8XxXkpOaTYytUwi2mafjUg"><i class="fab fa-spotify"></i></a>
    </div>
    <footer class="footer">
    </footer>
  </div>
</body>
</html>
