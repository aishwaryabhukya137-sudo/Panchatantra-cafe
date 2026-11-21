Panchatantra Cafe — image and mobile navigation fixes

Replace index.html and styles.css with these updated files, and upload menu.js too.

Fixes:
- Main content photographs now show their full image and natural proportions instead of being cropped into fixed-height boxes.
- Image wrappers expand naturally, including wrappers used on the Books, Games and Events pages, provided those pages load this shared styles.css.
- The mobile hamburger opens on the first tap and closes on the second tap. Selecting a link, tapping outside, pressing Escape, or switching to desktop closes it.
- The homepage loads menu.js automatically.

IMPORTANT FOR OTHER HTML PAGES:
The uploaded ZIP contained only index.html and styles.css, not books-and-games.html, Event.html, or the other page files. To enable the same reliable hamburger behaviour on each of those pages, add this line immediately before </body>:
<script src="menu.js" defer></script>
Make sure each page links to the updated styles.css.

Keep all existing photos, logo, and other HTML pages in their current website folder. The original upload did not include those image assets or other HTML pages, so they are not duplicated in this ZIP.
