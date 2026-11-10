MERLIN 404.EXE SENSI — setup

1. Open index.html in a text editor.
2. Find GET_KEY_URL and replace the example URL with your real Get Key website.
3. Find WHATSAPP_NUMBER and replace 234XXXXXXXXXX with your WhatsApp number (digits only, including country code).
4. DEMO ONLY: MERLIN-DEMO-2026 is a sample key. The key list is visible in browser source and is NOT secure for selling access.
5. Before selling keys, connect the login to a server-side key validator (for example, a Supabase Edge Function). Never put a secret service-role key in this HTML.
6. Upload index.html to GitHub Pages or another static host.

Device detection note:
Browser APIs generally do not expose exact total phone storage. The page shows the browser's site quota estimate when available and lets users select their actual phone storage manually. RAM detection is approximate and may be unavailable.
