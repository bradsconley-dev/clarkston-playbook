# Clarkston Playbook

An offline basketball play designer for Clarkston Wolves basketball. Draw offensive and defensive plays on the Dan Fife Fieldhouse floor, step through them, animate them and keep a playbook for each team.

Version: v1.0.0-clarkston

## Features
- Half-court and full-court views on the Clarkston floor (a drawn NFHS court is available as a fallback)
- Offense 1-5, defense X1-X5 and a ball, with quick sets (5-out, 4-out 1-in, 1-4 high, 2-3 zone, man-to-man)
- Standard diagram lines: cut, dribble, pass, screen and handoff
- Multi-step plays with smooth animation
- Separate playbooks for Varsity, JV and Freshman
- Search, duplicate, rename, reorder and delete plays
- Backup and restore as a JSON file, save each step as a PNG, and print

## Use
Open the site on a phone or iPad and use **Add to Home Screen**. After the first visit it works with no internet connection.

To get an update on an installed copy, fully close the app and reopen it.

## Data
Plays are stored only on the device, in the browser's local storage (keys start with `cl_pb_`). Nothing is sent anywhere. Use **Backup** regularly to keep a copy of your plays.

## Files
- `index.html` - the whole app in one file
- `manifest.webmanifest` - install settings
- `sw.js` - offline cache
- `icons/` - app icons
