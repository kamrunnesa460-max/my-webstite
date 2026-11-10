BANGLADESH TRAINZ - SELF-HOSTED VERSION
=======================================

FILES
  index.html    The public website. Upload this.
  content.json  All your text, assets, links, colours. Upload this.
  images/       Your photos. Upload this folder.
  admin.html    YOUR PRIVATE EDITOR. Keep it on your computer. DO NOT upload it.

PUBLISH (GitHub + Cloudflare Pages)
  1. On GitHub open your repository, click Add file > Upload files.
  2. Upload index.html, content.json and the images folder. Do NOT upload admin.html.
  3. Cloudflare Pages redeploys by itself in about a minute.

EDIT YOUR SITE
  1. Double-click admin.html on your computer (opens in your browser).
  2. First time only: click Edit site > Data > choose your content.json under Import.
  3. Change anything: assets, download links, text, colours, covers.
  4. Click "Download content.json" at the top of the editor.
  5. Replace content.json on GitHub with the new file (Add file > Upload files).
  Visitors see the new version after Cloudflare redeploys.

PHOTOS
  Put photos in the images folder, upload them to GitHub, then in the editor open an
  asset and type the path under "or image path", for example images/wdm-3a.jpg
  (Uploading photos inside the editor also works, but makes content.json large.)

IF THE SITE LOOKS BROKEN ON CLOUDFLARE
  In Cloudflare: Speed > Optimization > turn OFF Rocket Loader, then purge the cache.
