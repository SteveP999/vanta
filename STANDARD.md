# Vanta Artist Site Standard

This repo follows the Hello Texas Records artist-site standard using Parsons Cross as the master structural template.

## Required structure

- `/images/artist`
- `/images/covers`
- `/images/logos`
- `/audio`
- `index.html`
- `songs.json`
- `latest.json`
- `radio.json`
- `update.bat`
- `STANDARD.md`
- `CNAME`

## Locked rules

- Keep the video system on every artist site.
- Every song object must include `videos: []` or a populated `videos` array.
- Do not use Singles, Featured Tracks, or All Tracks sections.
- Every album must include an album layout and an Album Tracks section.
- Use local relative image paths only for local assets.
