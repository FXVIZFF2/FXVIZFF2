npm install pacman-contribution-graph
# **Davi Ciriaco** - FXVIZFF2
### DESENVOLVEDOR JAVA CURSANDO DS

<div class="logos">
  <img src="https://skillicons.dev/icons?i=java,html,css,js,cpp,postman,github" alt="Logos" />
</div>
<script src="https://cdn.jsdelivr.net/npm/pacman-contribution-graph/dist/pacman-contribution-graph.min.js">
  import { ArcadeRenderer } from 'pacman-contribution-graph';


const renderer = new ArcadeRenderer({
	game: 'PacMan',
	username: 'your_username',
	platform: 'github', // or 'gitlab'
	gameTheme: 'github-dark', // 'github', 'github-dark', 'gitlab', or 'gitlab-dark'
	playerStyle: 'opportunistic', // Pac-Man only: 'conservative', 'aggressive', or 'opportunistic'
	svgCallback: (svg) => {
		// called with the generated SVG string
		document.getElementById('output').innerHTML = svg;
	},
	gameOverCallback: () => {
		console.log('Game over!');
	},
	pointsIncreasedCallback: (points) => {
		console.log('Score:', points);
	}
});
renderer.start();
</script>

