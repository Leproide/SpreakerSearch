# SpreakerSearch 

A simple web page to search for all episodes containing a specific keyword for a given Show ID, going backwards until the specified deadline. The episodes will be listed, and by clicking play, a player will start with the desired episode

# Required Configuration:

Change the show ID here by replacing CHANGEME:
```javascript
const baseUrl = "https://api.spreaker.com/v2/shows/CHANGEME/episodes";
```
You can find the show ID by click on ![immagine](https://github.com/user-attachments/assets/f0d25793-abca-4f64-95eb-4eb54ba54466) and embed options

Esample:
```html
<iframe src='https://widget.spreaker.com/player?show_id=1679776&theme=dark&playlist=show&playlist-continuous=true&chapters-image=true' width='100%' height='400px' frameborder='0'></iframe>
```
Show ID: 1679776

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

# Screenshot:

![immagine](https://github.com/user-attachments/assets/adb1f8b8-cdcf-4c36-9a80-790254efa65c)
![immagine](https://github.com/user-attachments/assets/2a9ff29d-0b48-4fc8-9064-93ce5d21da3a)


