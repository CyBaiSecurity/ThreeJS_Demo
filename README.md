# Three.js demo

A dark page with one lit cube. The cube spins on its own. Lighting is an ambient light plus one directional light. Three.js 0.160.0 loads from unpkg.

Serve this folder as the site root. The page requests `/main.js`, so a subpath misses the script.

```bash
python3 -m http.server 8000
```

Open http://127.0.0.1:8000/.
