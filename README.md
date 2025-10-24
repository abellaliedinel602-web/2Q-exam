<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Christmas Bash Poster</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background: linear-gradient (135 deg, #e3f2fd, #ffffff);
            color: #1565c0;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #0d47a1;
            color: white;
            padding: 25 px;
            font-size: 2.5 em;
            font-weight: bold;
            text-shadow: 1 px 1 px 3 px rgba (0,0,0,0.7);
            border-bottom: 5 px solid #42a5f5;
        }
        nav {
            background-color: #1976d2;
            padding: 10 px;
            font-size: 1.2 em;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15 px;
            padding: 5 px 10 px;
            border-radius: 5 px;
            transition: background-color 0.3 s;
        }
        nav a:hover {
            background-color: #42a5f5;
        }
        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20 px;
        }
        article {
            max-width: 700 px;
            margin: 20 px 0;
            padding: 20 px;
            background-color: #ffffff;
            border-radius: 15 px;
            box-shadow: 0 6 px 12 px rgba (0,0,0,0.15);
        }
        article h2 {
            color: #0d47a1;
            font-size: 1.8 em;
        }
        img {
            max-width: 100 %;
            height: auto;
            border-radius: 10 px;
            margin: 15 px 0;
            box-shadow: 0 4 px 8 px rgba (0,0,0,0.2);
        }
        aside {
            background-color: #e1f5fe;
            padding: 15 px;
            margin: 20 px;
            border-radius: 10 px;
            max-width: 300 px;
            box-shadow: 0 4 px 8 px rgba (0,0,0,0.1);
        }
        aside h3 {
            color: #0277bd;
            font-size: 1.4 em;
        }
        .details-grid {
            display: grid;
            grid-template-columns: repeat (auto-fit, minmax (200 px, 1 fr));
            gap: 15 px;
            margin: 20 px 0;
        }
        .detail-card {
            background-color: #f3e5f5;
            padding: 15 px;
            border-radius: 8 px;
            border: 2 px solid #ba68c8;
        }
        .detail-card h4 {
            color: #7b1fa2;
            margin-bottom: 10 px;
        }
        footer {
            background-color: #4caf50;
            color: white;
            padding: 15 px;
            font-size: 1 em;
            margin-top: 20 px;
        }
        .sparkle {
            position: absolute;
            top: 20 %;
            right: 10 %;
            font-size: 1.5 em;
            color: #ffd700;
            animation: sparkle 3 s ease-in-out infinite;
        }
         @ keyframes sparkle {
            0  %, 100 % { opacity: 0; transform: scale (0.5); }
            50 % { opacity: 1; transform: scale (1); }
        }
    </style>
</head>
<body>
    <div class="sparkle">✨</div>
    <header>
        ❄️ Holiday Bash Extravaganza! ❄️
    </header>
    <nav>
        <a href="#details">Party Details</a>
        <a href="#rsvp">RSVP</a>
        <a href="#fun">Fun Facts</a>
    </nav>
    <main>
        <article>
            <h2>Ho Ho Ho! Join the Christmas Celebration!</h2>
            <img src="https://via.placeholder.com/600x300/ff0000/ffffff?text=Festive+Christmas+Scene" alt="Joyful Christmas Party Atmosphere">
            <p>Deck the halls with boughs of holly and join your class/section for an unforgettable Christmas bash! Filled with laughter, games, and holiday spirit, this is the event you've been waiting for.</p>
        </article>
        <section id="details" class="details-grid">
            <div class="detail-card">
                <h4>Date & Time</h4>
                <p>December 17th, 2025<br>8:00 AM - 12:00 PM</p>
            </div>
            <div class="detail-card">
                <h4>Location</h4>
                <p>Unida Christian College, Main Campus<br>Address: Anabu 1-F Imus Cavite, Imus Philippines</p>
            </div>
            <div class="detail-card">
                <h4>Theme</h4>
                <p>Cozy & Comfort – Come dressed in your best outfits!</p>
            </div>
            <div class="detail-card">
                <h4>Bring Along</h4>
                <p>Holiday snacks, a wrapped gift for the gift exchange gifts!</p>
            </div>
            <div class="detail-card">
                <h4>Highlights</h4>
                <p>carol Singing, holiday trivia, photo booth, Interctive Games and a delicious buffet.</p>
            </div>
        </section>
        <aside id="fun">
            <h3>Christmas Fun Facts!</h3>
            <ul>
                <li>The first Christmas tree was decorated in Germany in the 16th century.</li>
                <li>Over 300 million Christmas trees are sold worldwide each year.</li>
                <li>The tradition of hanging stockings comes from the legend of St. Nicholas.</li>
            </ul>
        </aside>
        <article id="rsvp">
            <h2>Reserve Your Spot!</h2>
            <p>Spaces are limited! Reply to this poster or email rsvp@ucc-cavite.edu.ph by December 17th. Let's make memories that last a lifetime!</p>
        </article>
    </main>
    <footer>
        Hosted by 11-Romans Team | Merry Christmas and Happy New Year! 🎁
    </footer>
</body>
</html>
