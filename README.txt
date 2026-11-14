AXIOM LAB - WEBSITE AND INSTALLABLE APP
=======================================

What is in this folder
  index.html            The website (details, features, subjects, how to install)
  app.html              The Axiom Lab app itself
  manifest.webmanifest  Lets phones and computers install it as an app
  sw.js                 Makes it work offline after the first visit
  icons/                App icons

IMPORTANT: it must be put on a website (https) before it can be installed.
Opening index.html straight from the folder works for the app, but "Install" and
offline mode only work when the files are served from a web address.

Put it online for free (pick one)
  Netlify Drop (easiest, no account tricks)
    1. Go to app.netlify.com/drop
    2. Drag THIS whole folder onto the page.
    3. You get a web address. Share it. Done.

  GitHub Pages
    1. Make a new public repository on GitHub.
    2. Upload all the files in this folder (keep the icons folder).
    3. Settings > Pages > Deploy from branch > main, folder "/ (root)".
    4. Your site appears at https://YOURNAME.github.io/REPOSITORY/

Installing it (people who visit your address)
  Android Chrome : tap "Install the app" on the website, or menu > Install app.
  iPhone Safari  : Share button > Add to Home Screen.
  Computer       : install icon in the address bar of Chrome or Edge.

A real Android app file (.apk) for the Play Store
  After the site is online, paste its address into pwabuilder.com and choose
  Android. It builds the package for you. (Play Store needs a Google developer account.)

Updating later
  Replace app.html (and sw.js if it changed) with the new versions and upload again.
  People who already installed it see an "Update now" message the next time they open it.

Notes
  - Progress, accounts and passwords stay on each person's own device.
  - Ewe has no audio. French audio needs a French voice on the device.
