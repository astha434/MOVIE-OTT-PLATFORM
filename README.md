# Movie OTT Platform — HTML/CSS/JS

A simple, responsive Movie OTT (Over The Top) platform UI built with plain HTML, CSS and JavaScript.

This project is a static front-end demonstration of a movie streaming service layout. It showcases a homepage with featured content, a popular trending carousel powered by Swiper, and individual movie play/detail pages with embedded video support.

**Features:**
- Responsive layout for desktop and mobile.
- Movie carousels using Swiper for smooth navigation.
- Play/pause and modal video preview in the movie detail page.
- Search field UI and a left/right navigation bar with icons.
- Separate movie detail pages with cast, description and download links.

**License:** MIT

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Tech Stack:**
- HTML5
- CSS3 (responsive design and gradients)
- JavaScript (ES6)
- Swiper.js for carousels
- Boxicons (icon set)

**How to use / Run locally**
1. Clone or download the repository.
2. Open the folder in your editor or terminal, then simply open `index.html` in your browser to view the demo.
3. For a local server (recommended for video files), run a simple static server and visit `http://localhost:8000`:

	 - Using Python 3:
		 ```powershell
		 python -m http.server 8000
		 ```
	 - Or install `live-server` via npm for a live reload development server:
		 ```powershell
		 npm install -g live-server
		 live-server
		 ```

**Project Structure**
- `index.html` — Main landing page with carousels and navigation.
- `style.css` — Global styles and responsive layout rules.
- `main.js` — Initializes Swiper and handles video modal controls.
- `swiper-bundle.min.js`, `swiper-bundle.min.css` — Swiper assets.
- `img/` — Images used across the UI.
- `play-page/`, `play-page2/` — Play pages with video, cast, and downloads.
- `play-page.html`, `play-page2.html` — Individual movie detail pages.

**Customizing Movie Content**
- Update the `index.html` and the play pages to add or change movie cards, image paths, titles, and links.
- Replace or add media files inside the `play-page/` or `play-page2/` folders; update the video `src` in the corresponding play page.

**Notes & Known Limitations**
- This repository is a static UI demo without server-side support or authentication.
- Video files referenced locally may require running via a local server due to browser security around local file access.
- Some links refer to placeholder files — add real media files where needed.

**Contributing**
- Contributions are welcome — please fork the repository and submit a pull request with a clear explanation of changes.

**License**
- This project is available under the MIT License. See the [LICENSE](LICENSE) file for details.

---
