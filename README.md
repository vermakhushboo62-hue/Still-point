# Still Point

A small calming tool. Pick what you're feeling (overwhelmed, anxious, afraid, angry, betrayed, disappointed, jealous, small, unfocused, not enough, tired, sad, lonely) and get a guided breathing pattern, a short movement and a simple mind reset.

Plain HTML, no build step. Installable on phones and works offline after the first visit.

Hosted on Cloudflare Workers as static assets. The site lives in `public/`; `wrangler.jsonc` tells Cloudflare to serve that folder. Deploy command: `npx wrangler deploy`.
