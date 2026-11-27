# jazz-charts

Interactive guitar charts. Each song lives in its own folder as a single `index.html`.

- `/april/`: I'll Remember April (shell voicings, key picker, one-page cheat sheet with paste-in lyrics)
- `/ipanema/`: The Girl from Ipanema (barre or shell shapes, key picker, cheat sheet with paste-in lyrics)
- `/ipanema/piano/`: The Girl from Ipanema for piano (keyboard diagrams with finger numbers: left-hand root, right-hand 3rd + 7th)

Lyrics are never stored in this repo; each visitor pastes their own copy into the page.

Deployed on Vercel: every push to `main` goes live automatically.
To add a song: copy a song folder, edit the song data block in its core script (`HOME`, `CHORDS`, the bar lists, `PRESETS`) and the notes text, then add a link in `index.html`.
