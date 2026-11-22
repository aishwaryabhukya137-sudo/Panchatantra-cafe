PANCHATANTRA CAFE — WEBSITE FIX UPDATE

This is an UPDATE package for your existing repository, not a replacement for
your original photographs or HTML pages.

WHAT THIS FIXES
- Main cause of the blank/empty-looking sections: styles.css hid every .reveal
  element with opacity: 0, but the repository did not contain script.js to add
  the .visible class.
- Updated styles.css keeps content visible if JavaScript is unavailable.
- New script.js makes the mobile hamburger menu open/close correctly, supports
  Escape and menu-link closing, reveals page content, updates the footer year,
  and handles forms marked data-whatsapp-form.
- Existing cream/brown/terracotta palette is retained.

HOW TO APPLY
1. Download and EXTRACT this ZIP on your phone/computer.
2. Open your GitHub repository.
3. Choose Add file > Upload files.
4. Upload styles.css and script.js from the extracted folder to the repository ROOT.
5. Choose Commit changes.
6. Do not delete or replace your existing index.html, Event.html, other HTML pages,
   CNAME, or original JPG image files.
7. Wait for GitHub Pages to publish, then refresh the live site.

IMPORTANT
Uploading the ZIP itself as one file does NOT deploy the website. Extract it first
and upload the two files inside it to the repository root.
