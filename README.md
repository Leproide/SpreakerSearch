# SpreakerSearch 

A simple web page to search for all episodes containing a specific keyword for a given Show ID, going backwards until the specified deadline. The episodes will be listed, and by clicking play, a player will start with the desired episode

# Required Configuration:

Change the show ID here by replacing CHANGEME:
```javascript
const baseUrl = "https://api.spreaker.com/v2/shows/CHANGEME/episodes";
```

And customize:
```html
<h1>SEARCH RESULTS FOR CHANGEME</h1>
```
and
```html
episodeImg.src = "logo.png";
```
There may still be parts in Italian, I don’t feel like modifying it further.
Script for personal use, shared as is with no warranty of functionality.
