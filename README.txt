GAME RELEASE TRACKER — Install as an app
========================================

WHAT'S IN THIS FOLDER
  index.html            the app
  manifest.webmanifest  app name + icons (makes it installable)
  sw.js                 offline support (service worker)
  icon-192.png / 512    app icons

USE IT RIGHT NOW (no install)
  Double-click index.html to open it in your browser. Everything works
  except "install to home screen" and offline mode, which need hosting.

PUT IT ON YOUR PHONE / DESKTOP AS A REAL APP  (5 minutes, free)
  A PWA has to be served from a web address (https). Easiest free way:

  1. Go to  https://app.netlify.com/drop
  2. Drag THIS WHOLE FOLDER onto the page.
  3. Netlify gives you a link like  https://your-name.netlify.app
  4. Open that link on your phone:
       • iPhone (Safari):  Share ▸ Add to Home Screen
       • Android (Chrome): menu ⋮ ▸ Install app / Add to Home screen
       • Desktop Chrome/Edge: install icon in the address bar
  5. It now opens like a normal app, works offline, and keeps your games.

  (Any static host works too — GitHub Pages, Vercel, Cloudflare Pages.)

NOTES
  • Your added games and status picks are saved in that browser/app.
  • "Find cover art" pulls the image from Wikipedia and needs internet
    when you add a game; after that it's saved for offline use.
