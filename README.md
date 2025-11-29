<!DOCTYPE html>

<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Balkan Break - Examenreis Bulgarije</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {box-sizing: border-box; margin: 0; padding: 0;}
        body {font-family: 'Roboto', sans-serif; background-color: #f0f4f8;}
        header {background: linear-gradient(90deg, #1e3c72, #2a5298); color: white; text-align: center; padding: 50px 20px;}
        nav {display: flex; justify-content: center; background-color: #ffffff; box-shadow: 0 2px 6px rgba(0,0,0,0.1); position: sticky; top: 0; z-index: 100;}
        nav a {margin: 0 15px; padding: 15px; color: #1e3c72; text-decoration: none; font-weight: bold;}
        nav a:hover {color: #ff7e5f;}
        .container {max-width: 1200px; margin: 40px auto; padding: 0 20px;}
        h1, h2, h3 {color: #1e3c72;}
        p {line-height: 1.6; margin-bottom: 20px;}
        .button {background-color: #ff7e5f; color: white; border: none; padding: 12px 25px; border-radius: 8px; font-size: 1em; cursor: pointer; text-decoration: none;}
        .button:hover {background-color: #ff5722;}
        .section {margin-bottom: 50px;}
        .grid {display: flex; flex-wrap: wrap; gap: 20px;}
        .card {background: white; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); overflow: hidden; flex: 1 1 calc(33% - 20px); min-width: 280px;}
        .card img {width: 100%; height: 200px; object-fit: cover;}
        .card-content {padding: 15px;}
        .prijs {font-weight: bold; color: #ff7e5f; margin-top: 10px;}
        form input, form textarea {width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 6px;}
        .submit-btn {background-color: #1e3c72; color: white; border: none; padding: 12px 25px; border-radius: 6px; cursor: pointer; font-size: 1em;}
        .submit-btn:hover {background-color: #2a5298;}
        footer {background-color: #1e3c72; color: white; text-align: center; padding: 20px;}
        @media(max-width: 900px){.grid {flex-direction: column;}} 
    </style>
</head>
<body>

<header>
    <h1>Balkan Break</h1>
    <p>Examenreis naar Bulgarije voor examenleerlingen</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#over">Over</a>
    <a href="#activiteiten">Activiteiten</a>
    <a href="#fotos">Foto's</a>
    <a href="#boeken">Boeken</a>
</nav>

<div class="container section" id="home">
    <h2>Welkom bij Balkan Break</h2>
    <p>Beleef een onvergetelijke examenreis naar Bulgarije! Geniet van historische steden, zonovergoten stranden en ontspannende spa's. Kies uit onze zorgvuldig samengestelde pakketten en boek eenvoudig online.</p>
    <a href="#boeken" class="button">Bekijk Pakketten</a>
</div>

<div class="container section" id="over">
    <h2>Over de Reis</h2>
    <p>Onze examenreis combineert cultuur, ontspanning en avontuur. Bezoek de prachtige steden Plovdiv, Sunny Beach en Velingrad. Kies een pakket dat bij jouw wensen past: Basic, Premium of Ultra. Elk pakket bevat comfortabele hotels, vluchten en extra activiteiten.</p>
</div>

<div class="container section" id="activiteiten">
    <h2>Activiteiten</h2>
    <div class="grid">
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Plovdiv_Old_Town.jpg" alt="Plovdiv Wandeltour">
            <div class="card-content">
                <h3>Plovdiv Wandeltour</h3>
                <p>2 uur, €12</p>
                <a href="https://www.getyourguide.nl/plovdiv-l32528/plovdiv-wandeltour-met-gids-t277882/" target="_blank" class="button">Meer info / Boeken</a>
            </div>
        </div>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/f/f2/Plovdiv_Old_Town_Streets.jpg" alt="Oude Stad Tour">
            <div class="card-content">
                <h3>Oude Stad Wandeltour</h3>
                <p>2,5 uur, €15 p.p</p>
                <a href="https://www.getyourguide.nl/plovdiv-l32528/plovdiv-oude-stad-wandeltour-met-gids-audiogids-museum-t758376/" target="_blank" class="button">Meer info / Boeken</a>
            </div>
        </div>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/d3/Food_in_Bulgaria.jpg" alt="Voedselwandeling">
            <div class="card-content">
                <h3>Voedselwandeling Plovdiv</h3>
                <p>3 uur, €35 p.p</p>
                <a href="https://www.getyourguide.nl/plovdiv-l32528/voedselwandeling-plovdiv-bulgaarse-culinaire-en-culturele-tour-t763848/" target="_blank" class="button">Meer info / Boeken</a>
            </div>
        </div>
        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/2/27/Mountain_view_Bulgaria.jpg" alt="E-motorfietstocht">
            <div class="card-content">
                <h3>E-motorfietstocht Rodopegebergte</h3>
                <p>3–5 uur, €100 p.p</p>
            </div>
        </div>
    </div>
</div>

<div class="container section" id="fotos">
    <h2>Foto's van Bulgarije</h2>
    <div class="grid">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Plovdiv_Old_Town.jpg" alt="Plovdiv">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Sunny_Beach.jpg" alt="Sunny Beach">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Velingrad_Center.jpg" alt="Velingrad">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f2/Plovdiv_Old_Town_Streets.jpg" alt="Plovdiv Straat">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d3/Food_in_Bulgaria.jpg" alt="Bulgaarse gerechten">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/27/Mountain_view_Bulgaria.jpg" alt="Rodopegebergte">
    </div>
</div>

<div class="container section" id="boeken">
    <h2>Boek je Pakket</h2>

```
<div class="grid">
    <!-- Basic -->
    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Plovdiv_Old_Town.jpg" alt="Plovdiv">
        <div class="card-content">
            <h3>Basic Pakket – 3 Sterren</h3>
            <p>Totaalprijs: €754 p.p</p>
            <button class="button" onclick="openForm('basic')">Boek Nu</button>
            <div class="boek-formulier" id="basic">
                <form>
                    <input type="text" placeholder="Voor- en achternaam" required>
                    <input type="text" placeholder="Adres" required>
                    <input type="tel" placeholder="Telefoonnummer" required>
                    <input type="email" placeholder="E-mailadres" required>
                    <textarea placeholder="Opmerkingen" rows="4"></textarea>
                    <button type="submit" class="submit-btn">Verzend Boekingsverzoek</button>
                </form>
            </div>
        </div>
    </div>
    <!-- Premium -->
    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Sunny_Beach.jpg" alt="Sunny Beach">
        <div class="card-content">
            <h3>Premium Pakket – 4 Sterren</h3>
            <p>Totaalprijs: €823 p.p</p>
            <button class="button" onclick="openForm('premium')">Boek Nu</button>
            <div class="boek-formulier" id="premium">
                <form>
                    <input type="text" placeholder="Voor- en achternaam" required>
                    <input type="text" placeholder="Adres" required>
                    <input type="tel" placeholder="Telefoonnummer" required>
                    <input type="email" placeholder="E-mailadres" required>
                    <textarea placeholder="Opmerkingen" rows="4"></textarea>
                    <button type="submit" class="submit-btn">Verzend Boekingsverzoek</button>
                </form>
            </div>
        </div>
    </div>
    <!-- Ultra -->
    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Velingrad_Center.jpg" alt="Velingrad">
        <div class="card-content">
            <h3>Ultra Pakket – 5 Sterren</h3>
            <p>Totaalprijs: €1984 p.p</p>
            <button class="button" onclick="openForm('ultra')">Boek Nu</button>
            <div class="boek-formulier" id="ultra">
                <form>
                    <input type="text" placeholder="Voor- en achternaam" required>
                    <input type="text" placeholder="Adres" required>
                    <input type="tel" placeholder="Telefoonnummer" required>
                    <input type="email" placeholder="E-mailadres" required>
                    <textarea placeholder="Opmerkingen" rows="4"></textarea>
                    <button type="submit" class="submit-btn">Verzend Boekingsverzoek</button>
                </form>
            </div>
        </div>
    </div>
</div>
```

</div>

<footer>
    <p>&copy; 2025 Balkan Break. Alle rechten voorbehouden.</p>
</footer>

<script>
    function openForm(id) {
        const forms = document.querySelectorAll('.boek-formulier');
        forms.forEach(f => f.style.display = 'none');
        document.getElementById(id).style.display = 'block';
        document.getElementById(id).scrollIntoView({behavior: 'smooth'});
    }
</script>

</body>
</html>
