
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Call of Duty Mobile</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #101510;
            color: white;
        }

        header {
            background: #080b08;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h2 {
            color: #d6b43c;
            letter-spacing: 2px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        nav a:hover {
            color: #d6b43c;
        }

        .hero {
            height: 85vh;
            background:
            linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.8)),
            url("https://images.unsplash.com/photo-1519608487953-e999c86e7455");
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 8%;
        }

        .hero h1 {
            font-size: 55px;
            color: #d6b43c;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 18px;
            max-width: 550px;
            line-height: 1.6;
            margin-bottom: 25px;
        }

        .btn {
            background: #d6b43c;
            color: black;
            padding: 14px 25px;
            text-decoration: none;
            font-weight: bold;
            width: fit-content;
            border-radius: 5px;
        }

        .btn:hover {
            background: white;
        }

        section {
            padding: 60px 8%;
            text-align: center;
        }

        section h2 {
            color: #d6b43c;
            font-size: 32px;
            margin-bottom: 25px;
        }

        .cards {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
        }

        .card {
            background: #202820;
            padding: 25px;
            width: 280px;
            border-radius: 10px;
            border: 1px solid #444;
        }

        .card h3 {
            color: #d6b43c;
            margin-bottom: 15px;
        }

        .card p {
            line-height: 1.5;
        }

        footer {
            background: #080b08;
            padding: 25px;
            text-align: center;
            color: #aaa;
        }

        @media(max-width: 650px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 5px;
                font-size: 13px;
            }

            .hero h1 {
                font-size: 36px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h2>CALL OF DUTY</h2>

        <nav>
            <a href="#home">HOME</a>
            <a href="#about">ABOUT</a>
            <a href="#modes">MODES</a>
            <a href="#weapons">WEAPONS</a>
        </nav>
    </header>

    <div class="hero" id="home">
        <h1>CALL OF DUTY: MOBILE</h1>

        <p>
            Welcome to the battlefield!
            Experience intense multiplayer action,
            exciting missions, and battle royale
            adventures in Call of Duty Mobile.
        </p>

        <a class="btn"
           href="https://www.callofduty.com/mobile"
           target="_blank">
           PLAY NOW
        </a>
    </div>

    <section id="about">
        <h2>ABOUT THE GAME</h2>

        <p>
            Call of Duty Mobile is an action-packed
            mobile shooting game. Players can enjoy
            multiplayer battles, customize their
            loadouts, and compete with other players.
        </p>
    </section>

    <section id="modes">
        <h2>GAME MODES</h2>

        <div class="cards">

            <div class="card">
                <h3>MULTIPLAYER</h3>
                <p>
                    Fight against other players
                    in exciting team battles.
                </p>
            </div>

            <div class="card">
                <h3>BATTLE ROYALE</h3>
                <p>
                    Explore a large map and
                    compete to be the last player
                    or team standing.
                </p>
            </div>

            <div class="card">
                <h3>ZOMBIES</h3>
                <p>
                    Team up with friends and
                    face challenging zombie enemies.
                </p>
            </div>

        </div>
    </section>

    <section id="weapons">
        <h2>WEAPONS</h2>

        <div class="cards">

            <div class="card">
                <h3>ASSAULT RIFLES</h3>
                <p>Versatile weapons for different combat situations.</p>
            </div>

            <div class="card">
                <h3>SNIPER RIFLES</h3>
                <p>Precision-focused weapons for long-range gameplay.</p>
            </div>

            <div class="card">
                <h3>SHOTGUNS</h3>
                <p>Powerful weapons designed for close-range gameplay.</p>
            </div>

        </div>
    </section>

    <section>
        <h2>JOIN THE BATTLE</h2>

        <p>
            Are you ready to become a legendary soldier?
        </p>

        <br>

        <a class="btn"
           href="https://www.callofduty.com/mobile"
           target="_blank">
           OFFICIAL WEBSITE
        </a>
    </section>

    <footer>
        <p>© 2026 Call of Duty Mobile Fan Website</p>
        <p>Fan-made educational website. Not affiliated with Activision.</p>
    </footer>

</body>
</html>
