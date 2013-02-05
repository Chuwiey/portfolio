Simple Screen Scraper via Bookmarklet
======================================

You can add this by creating a bookmark with the following as the url:
<pre>javascript: void((function () { var e = document.createElement('script'); e.setAttribute('type', 'text/javascript'); e.setAttribute('charset', 'UTF-8'); e.setAttribute('src', 'https://raw.github.com/bfhappy/portfoilio/master/JavaScript/scraper.js?r=' + Math.random() * 99999999); document.body.appendChild(e) })());</pre>
and then dragging it to your bookmarks bar.

Once you do that, you can surf to any site, click on it, and it will show you a small box, similar to what Facebook shows you when you share a url.

Trying to guess the main content of a page isn't easy, but the assumption is that it is above-the-fold, somewhat centered and possibly semantically marked, either with HTML5 or with Open Graph.
If you don't like the image the was selected automatically, you can choose scroll between the images on the page (that are larger than the threshold set by the config).

Feel free to use this under a CC BY-SA 3.0 license.

The code for the bookmarklet button is:
<pre>javascript: void((function () { var e = document.createElement('script'); e.setAttribute('type', 'text/javascript'); e.setAttribute('charset', 'UTF-8'); e.setAttribute('src', 'YOUR_SCRAPER_JSFILE_URL_GOES_HERE?r=' + Math.random() * 99999999); document.body.appendChild(e) })());</pre>
