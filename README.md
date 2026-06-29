# For Riley

A little personal site &mdash; jokes, a trivia game, a memory-match game, encouragement, photo memory spots, and a love letter.

## How to put this on GitHub (so you have a real link to send him)

1. Go to github.com and create a new repository (e.g. `for-riley`). Keep it **public** so the site can be viewed by anyone with the link, but it won't show up anywhere unless someone has the exact URL.
2. Upload all the files in this folder (`index.html`, `love.html`, `support.html`, `jokes.html`, `timeline.html`, `reasons.html`, `bucketlist.html`, `playlist.html`, `comfortjar.html`, `secret.html`, `style.css`, and the `assets` folder) to that repo. Easiest way: on the repo page, click "Add file" → "Upload files," then drag all of them in.
3. Go to the repo's **Settings** tab → **Pages** (left sidebar).
4. Under "Build and deployment," set Source to "Deploy from a branch," branch to `main`, folder to `/ (root)`. Save.
5. Wait a minute or two, then refresh that Pages settings page &mdash; it'll show you a live URL like `https://yourusername.github.io/for-riley/`.

That link is what you send Riley.

## Before you send it

- Open `love.html` and personalize the letter with your own memories and words (already partly done).
- Open `jokes.html` and edit the `quiz` array near the bottom to swap in real questions about you two (already partly done).
- Open `timeline.html`, `reasons.html`, `bucketlist.html`, `playlist.html`, and `comfortjar.html` &mdash; each has bracketed placeholder text like `[your words here]` to replace with your real writing.
- Open `secret.html` and write the most personal message on the whole site &mdash; it's the payoff for going through everything else.
- Open `index.html` and find the line `var startDate = new Date('2024-01-01');` near the bottom &mdash; change it to the actual date you and Riley got together, so the "days of us" counter is accurate.
- Also in `index.html`, fill in the "Currently" section near the top of the page body with what you're both into right now.

## How the hidden page works

`secret.html` is linked from a locked envelope on the homepage. It only unlocks (becomes clickable) once Riley has visited every other content page on the same device/browser &mdash; love, support, jokes, timeline, reasons, bucketlist, playlist, and comfortjar. The homepage shows him a live count like "(5 / 8 opened)" so he knows there's more to find.

## Want to customize more?

See **CUSTOMIZE.md** in this folder &mdash; it's a plain-language, no-coding-experience-needed walkthrough for editing text, colors, adding photos, and adding new pages, all directly on github.com.
