# Rewind.PH — Living the Filipino 2000s Digital / Virtual Museum

**Tagline:** Living the Filipino 2000s  
**Supporting line:** Log in. Look back. See what shaped us.

A responsive, student-curated digital museum comparing popular culture from the 2000s with the present across three themes:

1. Body & Self-Image
2. Technology
3. Globalization

## What's included

- Responsive landing page and museum navigation
- Optional first-person 3D exhibition hall powered by Three.js (loaded from CDN), with a high ceiling, soft warm lighting, reflective floor, and animated double-glass entrance doors
- Entrance doors open automatically when the visitor enters and can be toggled by clicking the glass panels or the on-screen door control
- A navigable Group 2 credits wall inside the 3D museum
- 3 exhibition rooms and 15 then-versus-now artifact pairings
- Expanded artifact viewer with additional photographs and an individual caption for every displayed image
- Artifact search and category filters
- Timeline, visitor reflection prompts, SMART goal, implementation plan, resource list, success metrics, and risk responses
- Group 2 members and assigned roles on the landing page, About / Meet the Team section, and in-museum credits wall
- Optimized WebP copies of the supplied image artifacts
- A fallback artifact archive if WebGL / Three.js is unavailable

## Run locally

The simplest method is to serve the folder with a local web server:

```bash
cd rewindph_site
python -m http.server 8000
```

Then open `http://localhost:8000` in a modern browser. The 3D walkthrough uses Three.js from cdnjs, so an internet connection is needed for the 3D mode. The rest of the site and all artifact images are local. If the CDN or WebGL is unavailable, use the Artifact Archive section as the complete alternative.

## Group 2 — project team

| Member | Role |
|---|---|
| Conrad Santos | Leader / Software Developer |
| Christian Borja | Artifacts Researcher |
| Carl Josef Buizon | Artifacts Researcher |
| Charlene Padua | Artifacts Researcher |
| Clarence Joy Garcia | Graphic Designer |
| Clark Maverick Olinares | Artifacts Researcher |
| Connie Yadao | Artifacts Researcher |

## Add the team's GitHub repository

Open `index.html` and find:

```js
const SITE_CONFIG = { githubUrl: '' };
```

Paste the repository URL between the quotes. The GitHub repository link will appear in the footer automatically. A repository was not invented or created because no GitHub URL/account authorization was supplied.

## Publish with GitHub Pages

1. Create a repository named `rewind-ph` (or another team-approved name).
2. Upload the contents of this folder to the repository root. Keep `index.html`, `data.js`, and `assets/` together.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. Add the published URL and repository URL to the project documentation.

No build step or package installation is required.

## Content / curation notes

- The project brief identifies the exhibition focus as 2000–2010 and connects it to the present (2026).
- Several supplied technology artifacts were introduced before 2000: Nokia 5110 (1998), Windows 95 (1995), Sony CD/VCD players (1996–1998), original PlayStation (1994), and IBM Aptiva (1994). The museum identifies them as late-1990s predecessors whose influence continued into the 2000s, rather than claiming they were launched in the selected decade.
- Some celebrity and brand pairs are illustrative cultural comparisons, not direct successors or equivalent products.
- The iPhone 18 capabilities shown in the project description are retained as project-provided claims. Verify final device specifications and release details against an authoritative source before formal public assessment.
- Image captions are descriptive captions based on the supplied files and project notes. Before public publication, confirm image ownership, licenses, source URLs, and any required permissions / attributions.
- The uploaded video files were not included in this lightweight web build to avoid making the first visit slow. The image artifacts are optimized to WebP and kept locally in the `assets/` folder.

## Museum entrance and navigation

- Click **Enter Museum** to open the 3D gallery. The glass entrance doors animate open automatically.
- Use the **Doors: Open / Doors: Closed** control or click a glass door panel to toggle the entrance.
- Move with **W / A / S / D** or the arrow keys. Click the 3D canvas to enable mouse-look; click an artifact to open its full captioned gallery.
- Use the **GROUP 2 · CREDITS** shortcut to visit the in-museum credits wall.

## Project files

```text
rewindph_site/
├── index.html
├── data.js
├── README.md
└── assets/
    ├── body/
    ├── technology/
    └── globalization/
```

## Suggested Git commands

```bash
git init
git add .
git commit -m "Create Rewind.PH virtual museum"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/rewind-ph.git
git push -u origin main
```

Replace `YOUR-USERNAME` with the team's actual GitHub username and repository name.
