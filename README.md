HOW TO RUN
1. Host this folder over HTTPS (Netlify/Vercel/GitHub Pages/Cloudflare Pages) or locally: `python3 -m http.server 8080`, then open http://localhost:8080
2. Open it ONCE with internet, pick a model, tap "Download & start" and let it finish.
3. After that, it works offline. On a phone: browser menu > "Add to Home Screen".

NOTES
- Needs a WebGPU browser (Chrome/Edge on Android, Safari 18+ on iOS, desktop Chrome/Edge).
- For fully offline-first, download the web-llm library file from the jsDelivr URL in index.html into this folder and import it locally.
