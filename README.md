<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Christmas Bash Poster</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #e3f2fd, #ffffff);
            color: #1565c0;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #0d47a1;
            color: white;
            padding: 25px;
            font-size: 2.5em;
            font-weight: bold;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.7);
            border-bottom: 5px solid #42a5f5;
        }
        nav {
            background-color: #1976d2;
            padding: 10px;
            font-size: 1.2em;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #42a5f5;
        }
        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        article {
            max-width: 700px;
            margin: 20px 0;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }
        article h2 {
            color: #0d47a1;
            font-size: 1.8em;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 15px 0;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        aside {
            background-color: #e1f5fe;
            padding: 15px;
            margin: 20px;
            border-radius: 10px;
            max-width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        aside h3 {
            color: #0277bd;
            font-size: 1.4em;
        }
        .details-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        .detail-card {
            background-color: #f3e5f5;
            padding: 15px;
            border-radius: 8px;
            border: 2px solid #ba68c8;
        }
        .detail-card h4 {
            color: #7b1fa2;
            margin-bottom: 10px;
        }
        footer {
            background-color: #4caf50;
            color: white;
            padding: 15px;
            font-size: 1em;
            margin-top: 20px;
        }
        .sparkle {
            position: absolute;
            top: 20%;
            right: 10%;
            font-size: 1.5em;
            color: #ffd700;
            animation: sparkle 3s ease-in-out infinite;
        }
        @keyframes sparkle {
            0%, 100% { opacity: 0; transform: scale(0.5); }
            50% { opacity: 1; transform: scale(1); }
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
            <h2>Ho Ho Ho! Join the Ultimate Christmas Celebration!</h2>
            <img src="https://via.placeholder.com/600x300/ff0000/ffffff?text=Festive+Christmas+Scene" alt="Joyful Christmas Party Atmosphere">
            <p>Deck the halls with boughs of holly and join your class/section for an unforgettable Christmas bash! Filled with laughter, games, and holiday spirit, this is the event you've been waiting for.</p>
        </article>
        <section id="details" class="details-grid">
            <div class="detail-card">
                <h4>Date & Time</h4>
                <p>December 22nd, 2023<br>7:00 PM - 11:00 PM</p>
            </div>
            <div class="detail-card">
                <h4>Venue</h4>
                <p>Auditorium, Main Campus<br>Address: 123 Holiday Lane</p>
            </div>
            <div class="detail-card">
                <h4>Theme</h4>
                <p>Red & Green Gala – Come dressed in your best festive outfits!</p>
            </div>
            <div class="detail-card">
                <h4>Bring Along</h4>
                <p>Holiday snacks, a wrapped gift for the gift exchange, and your dancing shoes!</p>
            </div>
            <div class="detail-card">
                <h4>Highlights</h4>
                <p>Karaoke carols, holiday trivia, photo booth, and a delicious buffet.</p>
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
            <p>Spaces are limited! Reply to this poster or email rsvp@christmasbash.edu by December 18th. Let's make memories that last a lifetime!</p>
        </article>
    </main>
    <footer>
        Hosted by Your Class/Section Team | Merry Christmas and Happy New Year! 🎁
    </footer>
</body>
</html>
