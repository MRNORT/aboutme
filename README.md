<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #2E3440;
            color: #ECEFF4;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
        }

        .container {
            text-align: center;
            max-width: 500px;
            opacity: 0;
            animation: fade-in 1s forwards;
            padding: 40px;
            background: linear-gradient(135deg, #8FBCBB, #5E81AC, #81A1C1, #5E81AC);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }

        @keyframes fade-in {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }

        .highlight {
            font-weight: 600;
        }

        .social-icons {
            margin-top: 30px;
        }

        .social-icons a {
            display: inline-block;
            margin: 0 10px;
            color: #ECEFF4;
            font-size: 1.5rem;
            transition: transform 0.3s ease;
        }

        .social-icons a:hover {
            transform: translateY(-3px);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>About Me</h1>
        <p>hey im<span class="highlight"> tron</span> idunno why u here but this is a about me page so</p>
        <p>i like rhythm games and touhou i watch anime and i (somtimes) make music i dunno what to put in here
        <p>im always confused its normal trust me im stupid its also normal im 999% lazy its normal and im bored all the time its normal :O</p>
        <div class="social-icons">
            <a href="https://discordapp.com/channels/@me/553752561572904963/" target="_blank" rel="noopener noreferrer"><i class="fab fa-discord"></i></a>
            <a href="https://steamcommunity.com/id/tron12HD/" target="_blank" rel="noopener noreferrer"><i class="fab fa-steam"></i></a>
            <a href="https://open.spotify.com/artist/3oEXpQbY5v3gHG1xfOPPLE?si=8XxXkpOaTYytUwi2mafjUg" target="_blank" rel="noopener noreferrer"><i class="fab fa-spotify"></i></a>
        </div>
    </div>

    <!-- Font Awesome Icons (CDN) -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/js/all.min.js" crossorigin="anonymous"></script>
</body>
</html>
