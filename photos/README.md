# Trip photos

Photos in this folder are shown in the **Trip Photos** section of the website.

## Adding a photo

1. **Check permission.** Only add photos the sender took, and make sure the people pictured (and parents of any children) are happy to be on the club website.
2. **Resize it.** Phone photos are big. Aim for about 1600 px wide and under 500 KB (any photo app's "resize" or "export" option will do).
3. **Name it simply**, using lower case and hyphens, with no spaces, e.g. `2026-04-deep-creek-damper.jpg`.
4. **Upload it** into this `photos/` folder. On GitHub: open the folder, then **Add file → Upload files → Commit changes**.
5. **Add a line to the list** in `index.html`. Find `const TRIP_PHOTOS = [` near the bottom of the file and add:

   ```js
   { src: 'photos/2026-04-deep-creek-damper.jpg', caption: 'Damper cook-off', trip: 'Deep Creek Easter', date: 'April 2026' },
   ```

   The caption is also used as the image description for screen readers, so describe what's in the photo.
6. Delete the placeholder lines (the ones with `src: ''`) once real photos are in.

Photos show in the order they're listed. To remove a photo, delete its line and the file.
