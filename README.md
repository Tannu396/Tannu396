<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #111;
            color: #fff;
        }

        header {
            background-color: #000;
            padding: 10px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: space-between;
            padding: 10px;
            background-color: #000;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px;
        }

        section {
            padding: 20px;
        }

        .main-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .movie-card {
            background-color: #333;
            border-radius: 8px;
            margin: 10px;
            overflow: hidden;
            width: 200px;
        }

        .movie-card img {
            width: 100%;
            height: auto;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #000;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Netflix Clone</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">TV Shows</a>
        <a href="#">Movies</a>
        <a href="#">My List</a>
    </nav>

    <section>
        <h2>Popular Movies</h2>
        <div class="main-content">
            <!-- Movie cards go here -->
            <div class="movie-card">
                <img src="https://via.placeholder.com/200x300" alt="Movie 1">
                <h3>Movie 1</h3>
            </div>

            <div class="movie-card">
                <img src="https://via.placeholder.com/200x300" alt="Movie 2">
                <h3>Movie 2</h3>
            </div>

            <!-- Add more movie cards as needed -->
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Netflix Clone</p>
    </footer>
</body>
</html>
