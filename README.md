# Cycloo Racing Game

Cycloo is a lightweight browser-based cycling game. Pick a nickname and a team, then race against bots directly in your browser.

## Quick start

The following steps come from `readme.txt`:

1. Clone or extract this repository.
2. Open a terminal in the project directory.
3. Run `python3 -m http.server`.
4. Open <http://localhost:8000> in your web browser.

Start by opening `index.html`.

## Main pages

- **index.html** – landing page where you set your player name and team before starting a race.
- **course.html** – zoomed racing view where cyclists move automatically. When someone finishes, you are redirected to `resultat.html`.
- **resultat.html** – displays the winner of the race and lets you play again.
- **cycloo_course.html** – alternate cartoon-style race that uses bonus "pastilles". It ends on `cycloo_resultats.html`, which links to `cycloo_classement.html` for global rankings.

All files are plain HTML and JavaScript, so you can tweak them freely to customize the game.
