<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Balkan Break - Examenreis Bulgarije</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {box-sizing: border-box; margin: 0; padding: 0;}
        body {font-family: 'Roboto', sans-serif; background-color: #f5f6fa; color: #333;}
        header {background: linear-gradient(135deg, #4facfe, #00f2fe); color: white; padding: 60px 20px; text-align: center;}
        header h1 {font-size: 3em; margin-bottom: 10px;}
        header p {font-size: 1.2em;}
        nav {display: flex; justify-content: center; background-color: #fff; box-shadow: 0 2px 6px rgba(0,0,0,0.1); position: sticky; top: 0; z-index: 100;}
        nav a {margin: 0 20px; padding: 15px; text-decoration: none; color: #4facfe; font-weight: bold; transition: 0.3s;}
        nav a:hover {color: #00f2fe;}
        .container {max-width: 1200px; margin: 40px auto; padding: 0 20px;}
        h2 {color: #4facfe; margin-bottom: 20px;}
        p {margin-bottom: 20px; line-height: 1.6;}
        .button {background-color: #4facfe; color: white; border: none; padding: 12px 25px; border-radius: 8px; cursor: pointer; text-decoration: none; display: inline-block; margin-top: 10px; transition: 0.3s;}
        .button:hover {background-color: #00f2fe;}
        .grid {display: flex; flex-wrap: wrap; gap: 20px;}
        .card {background: #fff; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.1); flex: 1 1 calc(33% - 20px); min-width: 280px; display: flex; flex-direction: column;}
        .card img {width: 100%; height: 200px; object-fit: cover;}
        .card-content {padding: 20px; flex: 1; display: flex; flex-direction: column; justify-content: space-between;}
        .prijs {font-weight: bold; color: #ff7e5f; margin-top: 10px;}
        form input, form textarea {width: 100%; padding: 10px; margin: 10px 0; border-radius: 6px; border: 1px solid #ccc;}
        .submit-btn {background-color: #4facfe; color: white; padding: 12px 20px; border: none; border-radius: 6px; cursor: pointer; font-size: 1em;}
        .submit-btn:hover {background-color: #00f2fe;}
        .boek-formulier {display: none; margin-top: 15px; padding: 20px; background-color: #f0f4f8; border-radius: 8px;}
        footer {background-color: #4facfe; color: white; text-align: center; padding: 20px; margin-top: 50px;}
        @media(max-width: 900px) {.grid {flex-direction: column;}}
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

<div class="container" id="home">
    <h2>Welkom bij Balkan Break</h2>
    <p>Beleef een onvergetelijke examenreis naar Bulgarije! Ontdek de historische steden Plovdiv, Sunny Beach en Velingrad. Geniet van zon, cultuur en avontuur en kies het pakket dat bij jou past.</p>
    <a href="#boeken" class="button">Bekijk Pakketten</a>
</div>

<div class="container" id="over">
    <h2>Over de Reis</h2>
    <p>Onze examenreis combineert cultuur, ontspanning en avontuur. Kies uit drie pakketten: Basic, Premium en Ultra, elk met comfortabele hotels, vluchten en extra activiteiten afgestemd op examenleerlingen.</p>
</div>

<div class="container" id="activiteiten">
    <h2>Activiteiten</h2>
    <div class="grid">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1587403763623-5de3b9db7ff3?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Plovdiv Wandeltour">
            <div class="card-content">
                <h3>Plovdiv Wandeltour</h3>
                <p>2 uur, €12</p>
                <a href="https://www.getyourguide.nl/plovdiv-l32528/plovdiv-wandeltour-met-gids-t277882/" target="_blank" class="button">Meer info / Boeken</a>
            </div>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1597736669384-4d20f92e4745?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Oude Stad Tour">
            <div class="card-content">
                <h3>Oude Stad Wandeltour</h3>
                <p>2,5 uur, €15 p.p</p>
                <a href="https://www.getyourguide.nl/plovdiv-l32528/plovdiv-oude-stad-wandeltour-met-gids-audiogids-museum-t758376/" target="_blank" class="button">Meer info / Boeken</a>
            </div>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1617196030545-b3f31f0dfb1b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Voedselwandeling">
            <div class="card-content">
                <h3>Voedselwandeling Plovdiv</h3>
                <p>3 uur, €35 p.p</p>
                <a href="https://www.getyourguide.nl/plovdiv-l32528/voedselwandeling-plovdiv-bulgaarse-culinaire-en-culturele-tour-t763848/" target="_blank" class="button">Meer info / Boeken</a>
            </div>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="E-motorfietstocht">
            <div class="card-content">
                <h3>E-motorfietstocht Rodopegebergte</h3>
                <p>3–5 uur, €100 p.p</p>
            </div>
        </div>
    </div>
</div>

<div class="container" id="fotos">
    <h2>Foto's van Bulgarije</h2>
    <div class="grid">
        <img src="https://images.unsplash.com/photo-1572980650993-53a5a95fcf7f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Plovdiv">
        <img src="https://images.unsplash.com/photo-1569874739929-9ecf08396bb5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Sunny Beach">
        <img src="https://images.unsplash.com/photo-1508804185872-d7badad00f7d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Velingrad">
    </div>
</div>

<div class="container" id="boeken">
    <h2>Boek je Pakket</h2>
    <div class="grid">
        <!-- Basic Pakket -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1587403763623-5de3b9db7ff3?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Basic Pakket">
            <div class="card-content">
                <h3>Basic Pakket – 3 Sterren</h3>
                <p class="prijs">€754 p.p</p>
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
        <!-- Premium Pakket -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1569874739929-9ecf08396bb5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Premium Pakket">
            <div class="card-content">
                <h3>Premium Pakket – 4 Sterren</h3>
                <p class="prijs">€823 p.p</p>
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
        <!-- Ultra Pakket -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1508804185872-d7badad00f7d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Ultra Pakket">
            <div class="card-content">
                <h3>Ultra Pakket – 5 Sterren</h3>
                <p class="prijs">€1984 p.p</p>
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
