# h3-viewer
View Uber H3 cells on a map with support for h3 id's in long format

You can preview it at: https://uber-h3-viewer-long.glitch.me

## URL Parameters

The page supports url parameters to specify the initial position on the map, in two ways:

### lat/lng/zoom

The link https://wolf-h3-viewer-long.glitch.me/?lat=59.4&lng=24.7&zoom=10 will show the map centered around Tallinn, Estonia.

### One H3 cell id

The link https://wolf-h3-viewer-long.glitch.me/?h3=8a589c98475ffff will highlight an H3 cell of resolution 10 somewhere in Lagos, Nigeria.

### One H3 cell id in long format

The link https://wolf-h3-viewer-long.glitch.me/?h3l=623055622064439295 will highlight an H3 cell of resolution 10 somewhere in Lagos, Nigeria.

## Other Tips

Clicking on an H3 cell will copy its ID to the clipboard.

