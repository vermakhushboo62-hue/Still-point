# Still Point

A small calming tool. Pick what you're feeling (overwhelmed, anxious, afraid, angry, annoyed, impatient, betrayed, disappointed, jealous, small, unfocused, not enough, tired, bored, sad, lonely) or enjoying the present and get a guided breathing pattern, a short movement and a simple mind reset.

Hard feelings also have an Untangle step: stuck point, core belief, where it may come from, a kinder new belief, tiny efforts and places to use it.

Plain HTML, no build step. Installable on phones and works offline after the first visit.

Hosted on Cloudflare Workers as static assets. The site lives in `public/`; `wrangler.jsonc` tells Cloudflare to serve that folder. Deploy command: `npx wrangler deploy`.
