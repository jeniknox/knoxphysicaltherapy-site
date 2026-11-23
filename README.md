# Knox Physical Therapy website

A lightweight static website for Knox Physical Therapy. The site uses plain HTML, CSS, and JavaScript so it can be hosted on Cloudflare Pages, GitHub Pages, or another static host.

## Preview locally

Open `index.html` in a browser, or run a simple local server from this folder:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish

Upload the complete folder to a GitHub repository. Connect that repository to Cloudflare Pages and set the build output directory to `/` (no build command is needed). Add the custom domain in Cloudflare Pages after reviewing the published preview.

## Before launch

- Replace or supplement the original Flatirons landscape illustration with approved clinic photos if desired.
- Confirm service descriptions and professional credentials.
- Add the exact clinic street address and hours if you want them public.
- Confirm whether to retain the LinkedIn link and point it to the clinic's profile.
- Keep appointment intake in the existing secure scheduling or patient system; this site links to phone, text, and email only.
