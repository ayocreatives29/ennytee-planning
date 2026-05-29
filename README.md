# Tee & Enny Wedding Dashboard

This folder contains a self-contained wedding planning dashboard for Tee and Enny.

Open `index.html` in a browser to use it. No build step or internet connection is required.

## What It Covers

- Current planning status for a Q4 2026 Brisbane wedding
- Next decisions: officiating minister/date, venue model, invitation path
- Shared couple view for Bride, Groom, and joint ownership
- Interactive task board with saved progress
- Venue comparison table for Unidus and nearby alternatives
- Editable budget draft with live totals
- Inspiration board for suit, dress, shoes, wedding bands, decor, invite, and photoshoot ideas
- Shared notes for vows, attire, invitations, honeymoon, and overseas guest visas

## Notes

- Progress, budget figures, and notes are saved in the browser using local storage.
- Inspiration board images are saved in the browser too. This is useful for one device, but not true shared sync.
- Venue pricing has not been guessed. Add real quotes as they are received.
- `timeline-reference.jpg` is a local planning reference image used inside the dashboard.

## Mobile And Sharing

- `http://127.0.0.1:5179/` works only on this computer.
- A phone on the same Wi-Fi should use the computer's local address, for example `http://192.168.1.104:5179/`.
- For a proper shared couple dashboard with HTTPS, deploy this to GitHub Pages, Netlify, Vercel, or Firebase Hosting.
- For Bride and Groom to see the same live tasks, notes, budget, and uploaded ideas from different devices, add a small shared database and image storage layer such as Firebase or Supabase.
