# Install Andrew's Kodi addons (v1.2.1)

You need **Kodi 21 Omega**. Fire Stick / Shield / PC all work the same.

## INSTALL note (read this)

Keep **jurialmunkey**, **ResolveURL**, and other **stock dependencies** if they are already installed. **Do not replace them with forks.** Cumination (Andrew) requires the stock add-on ids (`script.module.resolveurl`, `script.module.six`, `script.module.kodi-six`, …).

**Cumination portrait fanart and site thumbs are addon-side.** They work in **Estuary** and any other skin. **Arctic Fuse 3 (Andrew) is optional** (dual-colour + extra framing). You do not need AF3 for portrait→fanart.

| Feature | What to install |
|---|---|
| Portrait thumbs as fanart / site logos | **Cumination (Andrew)** only (`plugin.video.cumination.andrew`) |
| Dual highlight colours / fanart extras polish | **Arctic Fuse 3 (Andrew)** (optional) |
| Skin widgets talking to Helper | **TMDb Helper (Andrew)** (only if you use AF3 Andrew) |

Stock Cumination (`plugin.video.cumination`) will not send portrait thumbs as fanart. Stock AF3 is not required and does not replace Cumination (Andrew).

Cumination is a **Video add-on**.

## Fast path: repository zip (Cumination + deps)

1. Enable **System → Add-ons → Unknown sources**.
2. Install **only** this zip: `repository.andrew-1.1.1.zip` (link below).
3. **Add-ons → Install from repository → Andrew's Kodi Workshop → Video add-ons → Cumination (Andrew)**.
4. Kodi pulls **stock** ResolveURL, resolveurl.xxx, six, kodi-six, requests, and the other Cumination requires from this same repository. You should not need to hunt those zips.

Then in Cumination (Andrew) settings turn on **Use thumbnail as fanart** and **Also use portrait thumbs as fanart / background**.

## Direct zip links (Release v1.2.1)

https://github.com/phantomgrimsalvo-svg/skin.arctic.fuse.3.andrew/releases/tag/v1.2.1

1. Workshop repository (install this first for Cumination + deps)  
   https://github.com/phantomgrimsalvo-svg/skin.arctic.fuse.3.andrew/releases/download/v1.2.1/repository.andrew-1.1.1.zip
2. Cumination (Andrew) 1.2.3 — only needed if you install from zip instead of from the repository  
   https://github.com/phantomgrimsalvo-svg/skin.arctic.fuse.3.andrew/releases/download/v1.2.1/plugin.video.cumination.andrew-1.2.3.zip
3. Arctic Fuse 3 (Andrew) 3.3.2 — **optional** dual-colour / framing polish  
   https://github.com/phantomgrimsalvo-svg/skin.arctic.fuse.3.andrew/releases/download/v1.2.1/skin.arctic.fuse.3.andrew-3.3.2.zip
4. TMDb Helper (Andrew) 6.18.0 — only if you use AF3 Andrew  
   https://github.com/phantomgrimsalvo-svg/skin.arctic.fuse.3.andrew/releases/download/v1.2.1/plugin.video.themoviedb.helper.andrew-6.18.0.zip

## Optional: Arctic Fuse 3 (Andrew)

If you want dual highlight (Colour A → Colour B) and letterbox/zoom/focus for portraits:

1. Install TMDb Helper (Andrew), then the AF3 (Andrew) zip.
2. **Settings → Interface → Skin → Arctic Fuse 3 (Andrew)**.
3. Skin settings → **Colour** and **Fanart extras**.

AF3 Andrew still needs jurialmunkey repo modules (`script.skinvariables`, `script.module.jurialmunkey`). Those stay stock from https://kodi.jurialmunkey.net/repository.jurialmunkey/ — not forked.

## What you should see

| Add-on | Where | Id |
|---|---|---|
| Workshop repository | Add-ons → Install from zip, then from repository | `repository.andrew` 1.1.1 |
| Cumination (Andrew) | Add-ons → Video add-ons | `plugin.video.cumination.andrew` 1.2.3 |
| Arctic Fuse 3 (Andrew) (optional) | Settings → Interface → Skin | `skin.arctic.fuse.3.andrew` 3.3.2 |
| TMDb Helper (Andrew) (optional) | Add-ons → Video add-ons | `plugin.video.themoviedb.helper.andrew` 6.18.0 |
