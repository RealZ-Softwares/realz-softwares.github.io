# RealZ website: project note

**Read `..\HANDOFF.md` (the RealZ Suite central handoff) first.**

- **Live:** https://animazgames-crypto.github.io (GitHub Pages, public repo `animazgames-crypto/animazgames-crypto.github.io`, branch `main`, root). It went live on 2026-09-28. It's free, with no custom domain yet.
- **What:** plain static HTML/CSS with no build step. The pages are `index.html` (apps), `forge.html` (features, Free vs Pro $19, FAQ), `support.html` (contact via the repo's GitHub Issues, so no public email), `privacy.html`, `refund.html` and `terms.html`. The icons in `img/` are the apps' own icons, resized.
- **Defaults I chose; the user can change them:** Forge Pro $19 one-time; 14-day refunds; up to 3 PCs; free 1.x updates; Lemon Squeezy as merchant of record; governing law Jamaica.
- **Not live yet (buttons are greyed out):** downloads (plan: installers on this repo's GitHub Releases) and the Buy Pro button (it becomes the Lemon Squeezy checkout link once the store exists).
- **Publish:** commit and `git push` in this folder; Git Credential Manager holds the login. Pages rebuilds in about 30 s.
