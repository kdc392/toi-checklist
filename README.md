# TOI Site Start Checklist (PWA)

Static files, no build step. Host the whole folder on any HTTPS host, open the URL on the phone,
then "Add to Home Screen" (Share menu on iPhone, browser menu on Android).

Local test:  python3 -m http.server 8000   ->  http://localhost:8000
Phone test needs HTTPS: deploy the folder (e.g. drag it onto Netlify Drop) or use a tunnel.

Open the app once with signal so the PDF library and fonts get cached; after that it works offline.
Bump VERSION in sw.js after every change you publish.
