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

Work through this list before publishing the draft. Search `index.html` for `draft-note` to find the visible placeholders.

Jeni Knox is the sole clinician. Write patient-facing copy about assessment and treatment in Jeni’s first-person voice, using “I,” “me,” and “my.”

Describe symptoms, movement, and patient goals directly. Avoid phrases like “daily living,” “daily life,” and “everyday activities.”

| Page area | Confirm, replace, or add |
| --- | --- |
| Homepage | Confirm the name and credentials, Lafayette location, and wording that appointments last 60–75 minutes. |
| Approach and services | Approve the patient concerns, treatment names, and descriptions for orthopedic conditions, pelvic health, gastrointestinal concerns, nerve concerns, and TMJ and craniofacial care. |
| Your first visit | Confirm whether patients need to complete paperwork in advance. Jeni approved both treatment photos for public use. |
| About Jeni | Confirm the bio, years in practice, credentials, and institute names. |
| Patient reviews | Jeni approved all four quotes and display names in the launch draft for public use. |
| FAQ: Medicare | Confirm whether separate Medicare information should be included. The FAQ already explains the practice’s insurance and superbill policy. |
| Contact | Confirm call, text, and email destinations. Add a scheduling link or LinkedIn profile only if there is a verified practice URL. |
| Sitewide | Confirm the logo, favicon, and Flatirons artwork. Verify the mobile menu, section links, FAQ controls, contact links, and any approved review cards. Remove all draft labels. |
| Domain launch | Plan redirects from the existing `/about/` and `/contact/` URLs to the corresponding sections. Check the apex and `www` addresses over HTTPS and confirm business email works after cutover. |

### Search and AI discovery at domain launch

Use descriptive headings, plain-language answers to patient questions, and confirmed practice details in future edits. Keep the practice name, Lafayette location, contact information, credentials, and service descriptions consistent across the site and public listings.

When Jeni asks how to switch `knoxphysicaltherapy.com` to the new site, perform an SEO and generative engine optimization (GEO) pass before the switch. If she reports that the switch already happened, run the pass on the live site and flag any fixes that need attention.

- Review page titles, descriptions, headings, service copy, and FAQ answers for clarity and accuracy. Keep important information available as readable page text.
- Check the canonical hostname, redirects from old URLs and alternate hostnames, crawl and indexing settings, and the production sitemap. Verify the live domain in Search Console and submit the sitemap when access is available.
- Review local business structured data against the visible site content. Check the Google Business Profile and public listings for consistent practice details when access is available.
