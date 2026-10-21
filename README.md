<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Beauchurévise AI</title>

<link rel="stylesheet" href="css/style.css">

<script defer src="js/ai.js"></script>
<script defer src="js/app.js"></script>

</head>

<body>

<header class="hero">

<h1>📚 Beauchurévise AI</h1>

<p>
Révise avec l'intelligence artificielle
</p>
</header>
<main>
<section class="card">
<h2>Importer ton cours</h2>

<textarea
id="courseInput"
placeholder="Colle ton cours ici">
</textarea>

<button id="saveCourse">
Analyser le cours
</button>

<div id="status"></div>

</section>

<section class="dashboard">

<button data-tool="summary">
🧠 Résumé
</button>

<button data-tool="flashcards">
🎴 Flashcards
</button>

<button data-tool="quiz">
📝 Quiz
</button>

<button data-tool="exam">
🎓 Examen
</button>

<button data-tool="chat">
👨‍🏫 Prof IA
</button>

<button data-tool="mindmap">
🗺 Carte mentale
</button>

<button data-tool="rap">
🎤 Version Rap
</button>

<button data-tool="gossip">
💅 Version Gossip
</button>

<button data-tool="podcast">
🎧 Podcast
</button>

<button data-tool="games">
🎮 Jeux
</button>

<button data-tool="advanced">
➕ Approfondir
</button>

</section>

<section class="card">

<h2>Résultat</h2>

<div id="output">

L'analyse apparaîtra ici.

</div>

</section>

</main>

<footer>

<p>
Beauchurévise AI © 2026
</p>

</footer>

</body>
</html>
