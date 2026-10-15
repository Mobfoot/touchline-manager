# Touchline Manager

A football (soccer) management game for your phone browser, in the spirit of the classic text-and-tables management games of the early 2000s. One 20-club English-style league, live text commentary, tactics, transfers, scouting, coaches and training.

All clubs and players are invented. It is a personal hobby project, free to play, with no adverts and no tracking.

## Play it

Open the game's web address in your phone browser. It is built for iPhone but works on any modern browser.

**Add it to your Home Screen first (recommended).** In Safari, tap the Share button, then **Add to Home Screen**. It then opens full screen like an app.

> Important: a game opened from the Home Screen icon is stored separately from one opened in Safari. Pick one way of playing and stick with it.

## Your save

The game saves automatically after every matchday, in your own browser. Nothing is sent anywhere.

Browsers can delete saved data, especially if you clear website data, use a private window, or do not open the site for a while. So back up now and then:

- **Club, Settings, Export save** gives you a block of text. Paste it into a note.
- **Import save** (same screen) or **Load saved game** (start screen) restores it.

## Playing

Tap **How to play** on the start screen for the full guide. In short: press **Continue** each matchday, kick off, and watch the commentary. Press **Tactics** during a match to change formation, mentality or make substitutions.

## Reporting a problem

Please send:

1. The **version** shown on the start screen and in Club, Settings (for example `v3`).
2. What you did, and what you expected to happen.
3. A screenshot if it is a display problem.
4. If it is a gameplay problem, your **Export save** text so it can be reproduced.

Useful feedback is often about feel: matches that are too high or low scoring, training or transfers that are too easy or too hard, anything confusing.

## Own database (real names)

The league data is a single block of JSON, separate from the game logic. **Club, Settings, Export database** shows the format. You can edit it and load it from the start screen with **Load database**. It needs an even number of clubs (4 to 24), 14 or more players per club, and 8 attributes per player. Real player and club names belong to their owners, so this repository ships only invented ones.

## For developers

Everything is plain HTML, CSS and JavaScript in one `index.html`, with no build step and no dependencies. Host it with GitHub Pages: Settings, Pages, deploy from the main branch, root folder.
