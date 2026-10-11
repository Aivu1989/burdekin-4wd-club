# Burdekin District 4 Wheel Drive Club Inc.

Website for the **Burdekin District 4 Wheel Drive Club Inc.** (Ayr, North Queensland). Incorporated in Queensland (IA17459) and affiliated with Four Wheel Drive Queensland.

## What's here

- `index.html` – the whole website in one file (styles and scripts load from public CDNs). GitHub Pages serves this file automatically.
- `photos/` – trip photos shown in the Trip Photos gallery. See `photos/README.md`.

## Publishing with GitHub Pages

1. In the repository go to **Settings → Pages**.
2. Under "Build and deployment" choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Save. The site appears at `https://<username>.github.io/burdekin-4wd-club/` after a minute or two.

## Common edits (all in `index.html`)

| What | Where |
| --- | --- |
| Contact email, photo email, photo text number | `EASY-TO-EDIT SETTINGS` block at the top of the main `<script>` near the bottom of the file |
| Trip photos | `TRIP_PHOTOS` list in the same settings block |
| Upcoming trips & events | `UPCOMING EVENTS` section: replace the `[To be confirmed]` text |
| Members' useful links | "Suggested by Members" box: copy the commented `<li>` template |

The contact form has no server behind it: pressing the button opens the visitor's own email app with the message filled in, so it works on GitHub Pages.
