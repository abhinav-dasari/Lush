# Lush

A simple static multi-page website (HTML/CSS) for a restaurant/food demo. The repository contains an index page, multiple food pages, a login page, and CSS stylesheets.

## Contents

- index.html — main site homepage
- login.html — login page (static form)
- food.html, food2.html .. food6.html — menu/food pages
- html(N).html — many numbered HTML pages (possible duplicates or variations)
- cse326(lushstyle).css, lushcss.css — stylesheets
- .gitattributes — git attributes file

Note: The repository contains many similarly named files (html(1).html ... html(96).html). Consider consolidating these into a clearer folder structure and using templates.

## How to view

1. Clone the repo:
   git clone https://github.com/abhinav-dasari/Lush.git
2. Open `index.html` in a browser, or run a simple local server:
   python3 -m http.server
   then visit http://localhost:8000

## Suggested improvements

- Clean up and rename files to remove parentheses and numbered duplicates (e.g., move repeated pages into a `pages/` directory).
- Combine and refactor repeated HTML into templates (use a static site generator or simple server-side includes).
- Merge and organize CSS. Remove unused styles and add responsive layout (media queries).
- Add accessibility improvements: semantic HTML5 tags, alt text for images, form labels, and proper heading order.
- Validate HTML/CSS and optimize images for performance.
- Add a LICENSE and CONTRIBUTING.md if you plan to accept contributions.

## Contact

Repo owner: abhinav-dasari

----

This README was generated and added by GitHub Copilot. It includes a brief analysis of repository contents and recommendations for next steps.