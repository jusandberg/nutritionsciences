# Nutrition Study Studio

A static study site containing Units 1–3, lessons, flashcards, quiz explanations and a calorie calculator. The dashboard has placeholders for 14 units. No installation or build step is required.

## Publish on GitHub Pages

1. Extract this ZIP on your computer.
2. Create a GitHub repository, for example `nutrition-study`.
3. Upload ALL extracted files to the repository root. `index.html` must be at the top level, not inside an extra folder. Upload the extracted files, not the ZIP itself.
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select the main branch and / (root), then Save.
7. Once deployment completes, GitHub displays the website URL in Settings → Pages.

GitHub Pages sites are generally publicly accessible. A private repository does not automatically make its Pages website private. Check the publication visibility available for your GitHub plan before publishing.

## Open locally

Extract all files together and open index.html in a browser. For predictable browser storage behaviour, use GitHub Pages or a local web server rather than relying on file:// storage.

## Progress

Progress saves in the browser with localStorage. It is not synced between devices. Existing progress on the ChatGPT-hosted site will not automatically transfer to a different origin such as GitHub Pages. No personal progress or credentials are included in this export.

## Files

- index.html: layout and styling
- app.js: lessons, practice, cards and calculator
- course.js: unit selection and per-unit progress
- data.js: Unit 1 content
- unit2.js and unit3.js: later-unit content
- PNG files: source figures used in lessons and questions
- .nojekyll: serves these files as a plain static website

## Content

Independent teaching overviews informed by the supplied course quizzes, our conversation and linked references. These are not official textbook reproductions or official answer keys. Ambiguous quiz items are marked and excluded from scoring.

To expand the course, add a unit data file, load it in index.html, register it in course.js and add its selector option. Keep all file paths relative so the site works at a GitHub Pages repository subpath.
