BIRD SPACE PROGRAM - installable web app
=========================================

What is in this folder
  index.html            the whole game (the 3D library is built in)
  sw.js                 service worker: saves the game so it plays offline
  manifest.webmanifest  app name, colours and icons
  icons/                app icons (Abbas with an orange ring and a rocket badge)

How to get it on your phone or iPad
  1. Put the folder on any HTTPS host. Easiest:
       - GitHub Pages: upload these files to a repo, then Settings > Pages
         > Deploy from branch > main > / (root)
       - or drag the folder onto app.netlify.com/drop
  2. Open the link and tap "Install App" on the title screen.
     On iPhone/iPad: Share > Add to Home Screen.

Notes
  - Opening index.html straight from your files still plays the game, but it
    cannot install or save for offline play. It has to be on a website.
  - To test on your computer: run  python3 -m http.server 8000  in this folder
    and open localhost:8000
  - Your progress is saved in the browser/app on that device.
