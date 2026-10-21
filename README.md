# Clara Site

This repository contains Clara’s public privacy policy page. The local copy was revised on October 21, 2026 for the project-conversation app; the release push publishes the matching policy through the existing GitHub Pages source.

Project files, conversations and generated memory prefer usable iCloud Drive, with device-local fallback. iCloud is the only current cloud storage path; Groq, OpenRouter and optional ElevenLabs still process content online. Earlier Supabase records and deployed services are historical and are not deleted by this source change.

## Policy maintenance

- Keep `index.html` and the published `docs/index.html` byte-identical and in sync with `../pickle/docs/v1/privacy-policy.md`.
- Source-to-claim evidence and remaining owner decisions are in `../pickle/docs/ops/clara-privacy-review.md`.
- Keep the existing page styling when making content corrections.
- Preview locally with `python3 -m http.server 8917 --bind 127.0.0.1`, then open `http://localhost:8917/` and check desktop and narrow widths.

## Publication

The app’s policy link targets `https://penson-yo.github.io/Clara/`. GitHub Pages uses `main:/docs`; `docs/index.html` is the published copy. Publication requires the authorized push and a successful Pages deployment. The root `index.html` remains the matching local preview source.

Before publication, confirm that `hello@heyclara.co` is monitored, resolve the retention and deletion decisions in the review, and reconcile the policy with the exact app build being released. GitHub Pages is configured under repository `Settings` → `Pages`; the public policy URL used by the app and App Store Connect must match the published destination.
