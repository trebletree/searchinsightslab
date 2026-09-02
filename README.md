# Search Insights Lab Site

This is a standard static HTML site. It does not require Node, React, npm, or a build command.

## Files

- index.html is the homepage and must remain in the repository root.
- assets/site.css contains the site styling.
- assets contains the Trebletree logo files.
- subpage-template.html is the starting point for new pages.

## Add a subpage

To create /services/combined-visibility-audit/:

1. Create folders named services and then combined-visibility-audit.
2. Copy subpage-template.html into services/combined-visibility-audit/.
3. Rename the copied file to index.html.
4. Edit its title, description, headline, and page content.
5. Link to it with href="/services/combined-visibility-audit/".

## GitHub

Put the CONTENTS of this folder in the repository root. Do not upload the ZIP itself. GitHub should show index.html, README.md, subpage-template.html, and assets at the top level.

## Sevalla static-site settings

- Branch: main
- Build command: leave blank
- Publish directory: .
- Index file: index.html

Every push to main should trigger a new deployment.
