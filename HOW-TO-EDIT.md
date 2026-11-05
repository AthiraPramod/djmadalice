# How to edit djmadalice.com (no coding needed)

All words, links, mixes, sets and gigs live in ONE file: **content.json**.

## Edit from your phone or laptop
1. github.com → repo **djmadalice** → tap **content.json** → tap the ✏️ pencil.
2. Change only the text **between quotes**. Keep commas, quotes and brackets.
3. Tap **Commit changes**. The site updates by itself in about a minute.

## What each part of content.json controls
| In content.json | Section on the site |
|---|---|
| about | Down the rabbit hole |
| transmissions | Transmissions (releases and mixes) |
| liveSets | Live from the booth (set videos) |
| nextStops | Next stops (upcoming gigs) |
| journeysSoFar | Journeys so far (past gigs; hidden while empty) |
| frames | Frames (press photos) |

## Copy-paste examples
- Mix:  { "title": "Coffee Rave Live", "date": "Nov 2026", "type": "Mix", "url": "https://soundcloud.com/..." }
- Set video:  { "title": "Sunset to Dark", "date": "Nov 2026", "url": "https://youtube.com/..." }
- Gig:  { "date": "22 Nov 2026", "event": "Coffee Rave", "venue": "Savora", "city": "Calicut" }
Put a comma between two items in the same list.

After a gig: cut it from nextStops and paste it into journeysSoFar.

## Add a photo
Repo → **photos** folder → **Add file → Upload files**. Then add a line to "frames" with its file name.

Something broke? Tell Sunny (Claude). Every change is saved in GitHub history and can be undone.
