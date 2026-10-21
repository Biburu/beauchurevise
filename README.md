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
    <p>Révise avec l'intelligence artificielle</p>
  </header>

  <main>
    <section class="card">
      <h2>Importer ton cours</h2>

      <textarea id="courseInput" placeholder="Colle ton cours ici"></textarea>

      <button id="saveCourse" type="button">
        Analyser le cours
      </button>

      <div id="status" aria-live="polite"></div>
    </section>

    <section class="dashboard">
      <button type="button" data-tool="summary">🧠 Résumé</button>
      <button type="button" data-tool="flashcards">🎴 Flashcards</button>
      <button type="button" data-tool="quiz">📝 Quiz</button>
      <button type="button" data-tool="exam">🎓 Examen</button>
      <button type="button" data-tool="chat">👨‍🏫 Prof IA</button>
      <button type="button" data-tool="mindmap">🗺 Carte mentale</button>
      <button type="button" data-tool="rap">🎤 Version Rap</button>
      <button type="button" data-tool="gossip">💅 Version Gossip</button>
      <button type="button" data-tool="podcast">🎧 Podcast</button>
      <button type="button" data-tool="games">🎮 Jeux</button>
      <button type="button" data-tool="advanced">➕ Approfondir</button>
    </section>

    <section class="card">
      <h2>Résultat</h2>
      <div id="output" aria-live="polite">
        L'analyse apparaîtra ici.
      </div>
    </section>
  </main>

  <footer>
    <p>Beauchurévise AI © 2026</p>
  </footer>
</body>
</html>
