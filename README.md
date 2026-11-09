# docs.direqt.ai redirect

GitHub Pages stub that claims `docs.direqt.ai` (whose DNS still CNAMEs to `direqt.github.io`) and sends every path to the same path on https://docs.chatforpublishers.ai (meta refresh + canonical; `404.html` preserves unknown paths via JS).

Why: direqt.ai is no longer ours (sold with the Direqt name; nameservers moved 2026-11-06). Keeping this host claimed prevents anyone else serving content on it via GitHub Pages and passes the old docs links to our docs. See `~/dev/direqt/infrastructure/CLAUDE.md`. Delete this repo if the `docs` record disappears from the direqt.ai zone.
