# How to edit djmadalice.com (no coding needed)

All the words, links and gigs live in ONE file: **content.json**.

## Edit on your phone or laptop
1. Open github.com → your repo **djmadalice** → tap **content.json**.
2. Tap the ✏️ pencil (Edit).
3. Change only the text **between the quotes**. Keep commas, brackets and quotes as they are.
4. Tap **Commit changes**. The site updates by itself in about 1 minute.

## Common edits
- **Add your Instagram:** "instagramUrl": "https://instagram.com/yourhandle"
- **Add your mix:** "soundcloudUrl": "https://soundcloud.com/..."
- **Add a gig** (copy a line, keep the comma between gigs):
  { "date": "22 Nov 2026", "event": "Coffee Rave", "venue": "Savora", "city": "Calicut" },
- **Move a gig to "Played":** cut it from upcomingGigs, paste into pastGigs.
- **Hide something:** leave it empty: "" or [].

## Add a new photo
1. In the repo, open the **photos** folder → **Add file → Upload files**.
2. Add a line to "photos" in content.json with the file name.

If anything breaks, tell Sunny (Claude) "the site looks broken" — every change is saved in GitHub history and can be undone.
