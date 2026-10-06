# ravish.digital

Static site for Ravish Digital Studio, deployed on Vercel with DNS at Cloudflare.

The source preserves the live September–October design and all four interactive portfolio cases. `index.html` uses local, separately served JavaScript, font and image files; `assets/w/` contains the 22 portfolio photographs. The Instagram contact, structured metadata and assistant use `@ravish.digital`.

The homepage requests no storage at the browser or CDN so a deployment can replace stale content. Content-hashed assets retain immutable caching; the social preview is served at `assets/rds-logo.png`.
