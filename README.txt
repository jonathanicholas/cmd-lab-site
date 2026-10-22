cmd lab website: files for hosting
==================================

Upload everything in this folder to the root of the web host for cmd-lab.eu.

  index.html            The whole website (pages, photo, logo, icons and styles are all built in).
  favicon.ico           Tab icon for browsers that look for /favicon.ico automatically.
  favicon.svg           Vector tab icon (also embedded in index.html).
  apple-touch-icon.png  Icon used when someone saves the site to a phone home screen.

Nothing else is required. The site loads its fonts from Google Fonts, so it needs
no font files of its own.

Before going live
-----------------
- Contact page: replace [EMAIL] and [ROOM] in index.html (search for them).
- Recruiting email: set up forwarding so recruit+postdoc@cmd-lab.eu and
  recruit+phd@cmd-lab.eu reach your inbox.
- CV: the CV link points to https://jonathanicholas.github.io/cv/ . Either update the
  PDF there, or add your CV to this folder (e.g. cv.pdf) and change that link to /cv.pdf.

Common hosts
------------
- GitHub Pages: put these files in a repository, enable Pages, and add a file named
  CNAME containing the single line  cmd-lab.eu  . Then point the domain's DNS at GitHub
  as described in GitHub's "custom domain" guide.
- Netlify / Cloudflare Pages: drag this folder into a new site, then add cmd-lab.eu as
  a custom domain in the site settings.
