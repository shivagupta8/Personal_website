# Personal_Website

A personal portfolio website featuring research, projects, and an interactive 3D project gallery built with Three.js.

---

## Features
- Responsive personal portfolio and resume
- Interactive 3D project gallery (Three.js)
- Project and research highlights
- Contact form
- Timeline and honors

---

## Setup Instructions

### 1. Prerequisites
- [Node.js](https://nodejs.org/) (for dependency management)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### 2. Install Dependencies
This project uses [Three.js](https://threejs.org/) for the 3D gallery. Install it with:

```bash
npm install three
```

### 3. Running Locally
You can use any static server to preview the site. For example, with [http-server](https://www.npmjs.com/package/http-server):

```bash
npx http-server .
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

Alternatively, you can simply open `index.html` directly in your browser, but some features (like ES module imports for Three.js) may require a local server.

---

## Usage

- **Homepage:** Shows your introduction, research, and project highlights.
- **3D Project Gallery:** Scroll to the "Interactive 3D Project Gallery" section. Hover over cubes to highlight, click to open project links.
- **Contact:** Use the contact form at the bottom to send a message (form is static by default).

---

## Deployment

You can deploy this site to any static hosting provider, such as:
- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [Firebase Hosting](https://firebase.google.com/products/hosting)

### Deploy to GitHub Pages
1. Commit your changes and push to your repository.
2. In your repo settings, enable GitHub Pages and set the source to the main branch (or `/docs` folder if you move files).
3. Access your site at `https://<username>.github.io/<repo-name>/`.

### Deploy to Vercel/Netlify
- Import your repo and follow the provider's instructions for static site deployment.

---

## Customization
- Edit `index.html` to update your content, sections, and images.
- Update `assets/js/three-projects-data.js` to change the 3D gallery projects.
- Modify styles in `assets/css/main.css` or the SASS files in `assets/sass/`.

---

## License
See [LICENSE.txt](LICENSE.txt) for details.
