# HCPSS Academies Development Site

All content development happens in the `gh-pages` branch.

## GitHub Pages

A preview site is available via GitHub Pages.  Unfortunately, the repository name is included in the URL structure.  You'll need to access the page at

`https://<github-user>.github.io/<repo-name>/academies/`

When asking for feedback, make sure to let everyone know that these will not be the official URLs when deployed to the main site.

## Local Development & Preparing for HCPSS.org

To test the Jekyll build without the GH pages repo name in the URL, pass an empty `baseurl` to the Jekyll command-line:

`jekyll serve --baseurl ''`
