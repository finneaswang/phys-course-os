# PHYS 157 · Course OS (v0)

Canvas-style, step-by-step course site for PHYS 157 (UBC, 2026W1), wired to the
Obsidian vault at `~/Documents/Obsidian/PHYS 157/`.

## Run locally — Docker

```bash
cd "~/Documents/PHYS Course OS"
docker compose up -d --build
# → http://localhost:8080
```

(Running via colima: `colima start` first if the VM isn't up.)

## Run without Docker

```bash
python3 -m http.server 8080
# or just double-click index.html
```

## Deploy to a free tier later

The image is a static nginx site — deployable as-is to Render / Railway /
Fly.io / any free static host (upload `index.html`). No backend required for v0;
progress is stored in the browser (localStorage).

## Roadmap (directed by Yike, step by step)

- [x] v0.1 — L01 Pre-class page (10 steps, wiki-graph, progress)
- [x] v0.2 — self-contained knowledge base: in-site concept pages (12) via
      wiki links + Concept library, interactive SVG demos (lattice vs gas
      animation, warming curve, heat-traffic diagram, IR spectrum)
- [ ] L01 lecture deep-dive page
- [ ] L02+ pages as materials arrive
- [ ] Practice engine (generate → review → question bank)
- [ ] FastAPI tutor backend (added to docker-compose when needed)

The site is fully self-contained — no external dependencies, no backend.
Concept pages live inside `index.html` (CONCEPTS object); the Obsidian vault
remains as an offline archive. `index.html` is bind-mounted into the nginx
container, so edits show up on refresh without a rebuild.
