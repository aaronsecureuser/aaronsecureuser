<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Spotify-like Website</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1e1e1e;
            color: #fff;
        }

        header {
            background-color: #000;
            padding: 1em;
            text-align: center;
        }

        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 2em;
        }

        .card {
            width: 200px;
            margin: 1em;
            background-color: #000;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .card-content {
            padding: 1em;
        }

        footer {
            background-color: #000;
            padding: 1em;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Spotify-like Website</h1>
    </header>

    <section>
        <!-- Card 1 -->
        <div class="card">
            <img src="album1.jpg" alt="Album 1">
            <div class="card-content">
                <h3>Album 1</h3>
                <p>Artist 1</p>
            </div>
        </div>

        <!-- Card 2 -->
        <div class="card">
            <img src="album2.jpg" alt="Album 2">
            <div class="card-content">
                <h3>Album 2</h3>
                <p>Artist 2</p>
            </div>
        </div>

        <!-- Add more cards as needed -->
    </section>

    <footer>
        <p>&copy; 2023 My Spotify-like Website</p>
    </footer>

</body>
</html>
