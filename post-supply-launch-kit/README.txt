post.supply launch kit, Oct 23 2026. Every page here is built and tested. Port, do not redesign.

post.supply/
  index-body.html     Home page body: hero + 3-step request, how it works, products,
                      why, landed-cost preview of the DDP app, closing, footer.
                      5 languages, day/night by local time, all micro-interactions.
  privacy-body.html   /privacy body (English + Spanish).
  head-snippet.html   <head> tags for both pages (titles, SEO, hreflang, fonts, config).
  favicon-32.png, apple-touch-icon.png, sitemap.xml   Serve at the root.

ddp.post.supply/
  index-body.html     The DDP landed-cost web app (installable). Body only.
  head-snippet.html   <head> tags: install, icons, fonts, config, service worker.
  manifest.webmanifest, sw.js, icon-*.png, apple-touch-icon.png, favicon-32.png
                      Serve at the root of ddp.post.supply.

Config (both sites, in head-snippet.html):
  window.PS_LEAD_ENDPOINT  lead API URL. Until set, requests are simulated.
  window.PS_TRACK          analytics hook.

Founder to fill before launch:
  ddp index-body.html: search CDEF (broker 350, port 650, inland 450 are placeholders)
                       and PS_CONFIG.dutyPreset (duty % per product, from the broker).
  privacy-body.html:   every [founder to confirm] / [por confirmar] placeholder.
