# MovieParadies4U
MovieParadies4U, we believe that every second counts! Dive into a paradise of short videos — packed with action, comedy, drama, and pure entertainment. Whether you have just a few minutes or an entire afternoon, our handpicked collection of quick clips will keep you thrilled, laughing, and coming back for more.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MovieParadies4U</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0c0c0c;
            color: #fff;
        }
        header {
            background-color: #1a1a1a;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
            color: #ff4c4c;
        }
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .video-card {
            background-color: #1a1a1a;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 10px #222;
            transition: transform 0.3s;
        }
        .video-card:hover {
            transform: scale(1.05);
        }
        video {
            width: 100%;
            display: block;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #1a1a1a;
            font-size: 0.9em;
            color: #777;
        }
    </style>
</head>
<body>

<header>
    <h1>MovieParadies4U</h1>
    <p>Short Videos, Big Entertainment!</p>
</header>

<main class="video-grid">
    <div class="video-card">
        <video controls src="video1.mp4"></video>
    </div>
    <div class="video-card">
        <video controls src="video2.mp4"></video>
    </div>
    <div class="video-card">
        <video controls src="video3.mp4"></video>
    </div>
    <!-- Add more videos as you like -->
</main>

<footer>
    &copy; 2025 MovieParadies4U. All rights reserved.
</footer>

</body>
</html>
<video controls autoplay muted>
    <source src="video1.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
<main class="video-grid">
    <div class="video-card">
        <video controls autoplay muted>
            <source src="video1.mp4" type="video/mp4">
        </video>
    </div>
    <div class="video-card">
        <video controls autoplay muted>
            <source src="video2.mp4" type="video/mp4">
        </video>
    </div>
    <div class="video-card">
        <video controls autoplay muted>
            <source src="video3.mp4" type="video/mp4">
        </video>
    </div>
</main>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #0c0c0c;
    color: #ffffff;
}

header {
    background-color: #1a1a1a;
    padding: 20px;
    text-align: center;
}

h1 {
    margin: 0;
    font-size: 3em;
    color: #ff4c4c;
    letter-spacing: 2px;
}

p {
    color: #bbbbbb;
    margin-top: 10px;
    font-size: 1.2em;
}

.video-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 30px;
}

.video-card {
    background-color: #1f1f1f;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0,0,0,0.5);
    transition: transform 0.3s, box-shadow 0.3s;
}

.video-card:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 12px rgba(0,0,0,0.8);
}

video {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 15px 15px 0 0;
}

footer {
    text-align: center;
    padding: 15px;
    background-color: #1a1a1a;
    font-size: 0.9em;
    color: #777;
}

@media (max-width: 600px) {
    h1 {
        font-size: 2em;
    }
}

