<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Life Of Ye</title>
    <style>
        /* Importing Google font for an old-time English feel */
        @import url('https://fonts.googleapis.com/css2?family=UnifrakturMaguntia&display=swap');

        body {
            font-family: "Comic Sans MS", cursive, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212; /* Dark background */
            color: #00bfff; /* Light blue text */
            text-align: center;
            line-height: 1.6;
        }
        header, main, footer {
            background: #121212; /* Dark background */
            color: #00bfff; /* Light blue text */
            padding: 1.5em;
        }
        /* Apply old-time font style to the header */
        h1 {
            font-family: 'UnifrakturMaguntia', cursive, sans-serif;
            font-size: 3em; /* Larger size for better impact */
            color: #1e90ff; /* Brighter blue for the header */
        }
        main {
            max-width: 1000px;
            margin: auto;
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0, 191, 255, 0.5); /* Light blue shadow */
            display: flex;
            align-items: flex-start;
            justify-content: space-between;
            text-align: left;
        }
        .about-text {
            flex: 1;
            padding-right: 20px;
            max-width: 600px;
        }
        h2 {
            font-size: 2em;
            color: #1e90ff; /* Brighter blue for headings */
        }
        p {
            font-size: 1.2em;
        }
        a {
            color: #1e90ff; /* Brighter blue for links */
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .image-gallery {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
        }
        .about img {
            width: 100%;
            max-width: 300px; /* All images will have the same width */
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 191, 255, 0.5); /* Light blue shadow */
            margin: 10px 0; /* Space between images */
        }
    </style>
</head>
<body>
    <header>
        <h1>The Life Of Ye</h1>
        <p>About the life of my goat Kanye</p>
    </header>
    <main class="about">
        <div class="about-text">
            <h2>About the life of Kanye West</h2>
            <p>
                Kanye West, born June 8, 1977, in Atlanta, Georgia, and raised in Chicago, Illinois, is one of the most influential and controversial figures in modern music and culture. He began his career as a producer for Roc-A-Fella Records in the early 2000s, where he gained recognition for his soulful and innovative production on Jay-Z’s The Blueprint. Determined to transition to rapping, West released his debut album, The College Dropout (2004), to critical and commercial acclaim. His blend of introspective lyrics, innovative production, and refusal to conform to hip-hop stereotypes cemented his place as a pioneer in the music industry. Over the next decade, Kanye released a string of genre-defining albums, including Late Registration, Graduation, and My Beautiful Dark Twisted Fantasy, solidifying his legacy as an artist unafraid to push boundaries.
                <br><br>
                Beyond music, Kanye ventured into fashion, launching the Yeezy brand in collaboration with Adidas, which became a global phenomenon. His fashion endeavors redefined the intersection of music and high fashion, blending streetwear with luxury aesthetics. Kanye also gained attention for his outspoken personality, often making headlines for his controversial statements and actions, including his infamous interruptions at award shows and his polarizing political endorsements. Despite the controversies, his cultural impact remains undeniable, influencing everything from music production to sneaker design and the broader creative landscape.
                <br><br>
                In his personal life, Kanye married reality TV star Kim Kardashian in 2014, with whom he shares four children. Their high-profile relationship and eventual divorce in 2021 were widely covered by the media. In recent years, Kanye has explored more personal and spiritual themes, notably with his gospel-inspired album Jesus Is King (2019), reflecting his renewed Christian faith. While his public image has been polarizing, Kanye West's contributions to music, fashion, and culture have left an indelible mark, making him one of the most talked-about and impactful figures of the 21st century.
            </p>
        </div>
        <div class="image-gallery">
            <img src="https://imgix.bustle.com/nylon/18426450/origin.jpg?w=1200&h=900&fit=crop&crop=faces&fm=jpg" alt="Kanye West">
            <img src="https://i.scdn.co/image/ab67616d0000b273880339078b7786730d2a02ba" alt="Graduation Album Cover">
            <img src="https://i.scdn.co/image/ab67616d0000b273428d2255141c2119409a31b2" alt="Late Registration Album Cover">
            <img src="https://m.media-amazon.com/images/I/71a0zG-Uj1L._UF1000,1000_QL80_.jpg" alt="Kanye West Album">
        </div>
    </main>
    <footer>
        <p>&copy; 2025 Connor K.</p>
    </footer>
</body>
</html>
