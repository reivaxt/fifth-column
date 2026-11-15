# The Fifth Column

A short serious game about caregiving, made for BN4701.

Wei Ming, a widowed father in Sengkang, cares for his mother Siew Lan (Ah Ma) after her stroke while raising Chloe and Marcus. He keeps track of everything on a whiteboard with four columns: Ah Ma, Chloe, Marcus and Work. For two days the player carries all four columns alone. Then a crisis comes, a fifth column appears, and the player chooses who to ask for help.

- **Length:** about 10 minutes
- **Plays on:** any modern browser, on a laptop or a phone. Sound is recommended.
- **Content note:** dementia, caregiver burnout and a missing-person scene.

## How to play it

**From a zip file:** unzip the folder and double-click `index.html`. Keep all the files together in the same folder. No installation or internet connection is needed (with no internet, the text simply uses a default font).

**From GitHub Pages:**
1. Create a public repository, for example `fifth-column`.
2. Upload everything inside this folder (not the folder itself), so that `index.html` sits at the top level of the repository.
3. Go to Settings → Pages, choose "Deploy from a branch", pick the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the game is live at `https://<your-username>.github.io/fifth-column/`.

To update the game later, upload the new `index.html` (and any new images) over the old ones.

## Files
- `index.html`: the whole game (HTML, CSS and JavaScript in one file)
- `*.jpg`: the illustrations for the story, pop-ups and cut scenes
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Notes
- Progress is saved in the player's own browser at the start of each day. Nothing is sent anywhere.
- Music and sound effects are generated in the browser; there are no audio files.
- For testing, add `#day1`, `#day2`, `#crisis`, `#help` or `#day3` to the end of the link to jump to that part.
