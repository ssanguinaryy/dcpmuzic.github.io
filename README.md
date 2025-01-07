<!DOCTYPE html>
<html>
<head>
    <div style="text-align: center;">
        <img src="images/face.png" alt="Фото" style="width: 150px;">
    </div>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DCP Music</title>
    <style>
        body {
            font-family: "Arial", sans-serif;
            color: #fff;
            background-color: #000;
            margin: 0;
            padding: 0;
        }
        header {
            background: #3A718D;
            color: #000;
            padding: 2rem 0;
            text-align: center;
            font-size: 2.5rem;
            text-transform: uppercase;
            letter-spacing: 4px;
        }
        nav {
            background: #111;
            padding: 1rem 0;
            text-align: center;
        }
        nav a {
            color: #5AA3C1;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.2rem;
        }
        nav a:hover {
            color: #fff;
        }
        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 1rem;
            background: #111;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(58, 113, 141, 0.5);
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            color: #5AA3C1;
            font-size: 1.8rem;
            border-bottom: 2px solid #5AA3C1;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }
        .track-list, .release-list {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1rem;
        }
        .track-item, .release-item {
            background: #222;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(58, 113, 141, 0.3);
            padding: 0.5rem;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .track-item img, .release-item img {
            width: 100%;
            max-width: 150px;
            border-radius: 5px;
            margin-bottom: 0.5rem;
        }
        .track-item p, .release-item p {
            margin: 0;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #5AA3C1;
            color: #fff;
            margin-top: 2rem;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        DCP Music
    </header>
    <nav>
        <a href="#tracks">Треки</a>
        <a href="#releases">Релизы</a>
        <a href="#contact">Контакты</a>
    </nav>
    <div class="container">
        <div class="section" id="tracks">
            <h2>Список треков</h2>
            <ul class="track-list">
                <li class="track-item">
                    <img src="images/oblozhka.png" alt="Обложка хепи пёздей">
                    <p><a href="https://soundcloud.com/dcpmusicprod/xepi-pyozdej" target="_blank" style="color: cyan;">хепи пёздей</a></p>
                </li>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka1.png" alt="Обложка 𝓴𝓪𝓻𝓪𝓫𝓪𝓼">
                    <p><a href="https://soundcloud.com/dcpmusicprod/1a36389c-53b3-4628-b101-86d3f83e977d" target="_blank" style="color: cyan;">𝓴𝓪𝓻𝓪𝓫𝓪𝓼</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka2.png" alt="Обложка #MONKEYSOUND">
                    <p><a href="https://soundcloud.com/dcpmusicprod/monkeysound" target="_blank" style="color: cyan;">#MONKEYSOUND</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka3.png" alt="Обложка freestyle obezvozhennye">
                    <p><a href="https://soundcloud.com/dcpmusicprod/freestyle-obezvozhennye" target="_blank" style="color: cyan;">freestyle obezvozhennye</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka4.png" alt="Обложка а может ты пидор?">
                    <p><a href="https://soundcloud.com/dcpmusicprod/a-mozhet-ty-pidor" target="_blank" style="color: cyan;">а может ты пидор?</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka5.png" alt="Обложка ХАХАЧУВЫСТРЕЛ">
                    <p><a href="https://soundcloud.com/dcpmusicprod/khakhachuvystrel" target="_blank" style="color: cyan;">ХАХАЧУВЫСТРЕЛ</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka6.png" alt="Обложка i dnt see u">
                    <p><a href="https://soundcloud.com/dcpmusicprod/i-dnt-see-u" target="_blank" style="color: cyan;">i dnt see u</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka7.png" alt="Обложка город.">
                    <p><a href="https://soundcloud.com/dcpmusicprod/gorod" target="_blank" style="color: cyan;">город.</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka8.png" alt="Обложка хепи пёздей remix 236 love диван...">
                    <p><a href="https://soundcloud.com/dcpmusicprod/xepi-pyozdej-remix-236-love" target="_blank" style="color: cyan;">хепи пёздей remix 236 love диван...</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka9.png" alt="Обложка Conqueror">
                    <p><a href="https://soundcloud.com/dcpmusicprod/conqueror" target="_blank" style="color: cyan;">Conqueror</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka10.png" alt="Обложка богоявление">
                    <p><a href="https://soundcloud.com/dcpmusicprod/bogoyavlenie" target="_blank" style="color: cyan;">богоявление</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka11.png" alt="Обложка тишина.">
                    <p><a href="https://soundcloud.com/dcpmusicprod/silence" target="_blank" style="color: cyan;">тишина.</a></p>
                </li>
                <li class="track-item">
                    <img src="images/oblozhka12.png" alt="Обложка порок.">
                    <p><a href="https://soundcloud.com/dcpmusicprod/porok" target="_blank" style="color: cyan;">порок.</a></p>
                </li>
            </ul>
        </div>
        <div class="section" id="releases">
            <h2>Новые релизы</h2>
            <ul class="release-list">
                <li class="release-item">
                    <img src="images/oblozhka10.png" alt="Обложка богоявление">
                    <p><a href="https://soundcloud.com/dcpmusicprod/bogoyavlenie" target="_blank" style="color: cyan;">богоявление</a></p>
                </li>
                <li class="release-item">
                    <img src="images/oblozhka11.png" alt="Обложка тишина.">
                    <p><a href="https://soundcloud.com/dcpmusicprod/silence" target="_blank" style="color: cyan;">тишина.</a></p>
                </li>
                <li class="release-item">
                    <img src="images/oblozhka12.png" alt="Обложка порок.">
                    <p><a href="https://soundcloud.com/dcpmusicprod/porok" target="_blank" style="color: cyan;">порок.</a></p>
                </li>
            </ul>
        </div>
    </div>
    <footer>
        &copy; 2025 DCP Music. Все права защищены. Музыка говно
    </footer>
</body>
</html>
