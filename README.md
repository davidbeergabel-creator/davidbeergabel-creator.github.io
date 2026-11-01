# davidbeergabel-creator.github.io

The top of this GitHub Pages address. It does two things:

- `index.html` sends visitors on to [Movie Night Mahjong](https://davidbeergabel-creator.github.io/movie-night-mahjong/).
- `.well-known/assetlinks.json` (once the Android app is signed) tells Android that the Movie Night Mahjong app and this website belong to the same owner, so the app opens full screen without a browser bar. Android only looks for it here, at the top of the address.

`.nojekyll` makes GitHub Pages publish the `.well-known` folder, which it would otherwise skip because its name starts with a dot.
