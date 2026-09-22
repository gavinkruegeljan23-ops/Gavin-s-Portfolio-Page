<!DOCTYPE html><html><head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>

    <style>
        body {
            font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, serif;
            width: 1024px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            font-size: 64pt;
            margin-bottom: 20px;
            text-shadow:
                0 0 6px #E033FF,
                0 0 12px #E033FF,
                0 0 24px #E033FF;
        }

        /* Flexbox container */
        .portfolio-box {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        figure {
            width: 200px;
            text-align: center;
        }

        figure img {
            width: 200px;
            height: auto;
            border: 1px solid #ccc;
            box-shadow: 2px 2px 6px rgba(0,0,0,0.2);
        }

        figcaption {
            font-size: 12pt;
            margin-top: 8px;
        }
    </style>
</head>

<body>

<h1>My Portfolio</h1>

<div class="portfolio-box">

    <!-- Drawing 1 -->
    <figure>
        <a href="images/alley-poster-full.png" target="_blank">
            <img src="file:///C|/Users/User 1/OneDrive/Pictures/Self-Portrait Movie Poster (1).png" alt="The Alley Movie Poster">
        </a>
        <figcaption>The Alley Movie Poster</figcaption>
    </figure>

    <!-- Drawing 2 -->
    <figure>
        <a href="images/springers-tour-full.png" target="_blank">
            <img src="file:///C|/Users/User 1/OneDrive/Pictures/Tour Poster Rough Draft copy.png" alt="Springers World Tour Poster">
        </a>
        <figcaption>The Springers World Tour Poster</figcaption>
    </figure>

    <!-- Drawing 3 -->
    <figure>
        <a href="images/self-portrait-full.jpg" target="_blank">
            <img src="file:///C|/Users/User 1/OneDrive/Pictures/Self Portrait Illustrator.JPG" alt="Self Portrait Illustrator">
        </a>
        <figcaption>Self Drawing on Illustrator</figcaption>
    </figure>

    <!-- Drawing 4 -->
    <figure>
        <a href="images/dragonclans-full.png" target="_blank">
            <img src="file:///C|/Users/User 1/OneDrive/Pictures/a1.PNG" alt="DragonClans Title Screen">
        </a>
        <figcaption>DragonClans Title Screen</figcaption>
    </figure>

    <!-- Drawing 5 -->
    <figure>
        <a href="images/museum-warhol-full.png" target="_blank">
            <img src="file:///C|/Users/User 1/OneDrive/Pictures/Screenshot 2026-09-15 124315.png" alt="Andy Warhol Style Museum">
        </a>
        <figcaption>The Museum — Andy Warhol Style</figcaption>
    </figure>

    <!-- Drawing 6 -->
    <figure>
        <a href="images/nike-photoshoot-full.png" target="_blank">
            <img src="file:///C|/Users/User 1/OneDrive/Pictures/Screenshot 2026-09-15 124742.png" alt="Nike Photoshoot">
        </a>
        <figcaption>Work Hard Play Hard Nike Photoshoot</figcaption>
    </figure>

</div>



</body></html>
