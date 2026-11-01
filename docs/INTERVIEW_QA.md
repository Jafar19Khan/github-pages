# GitHub Pages — Interview Questions & Answers

## 1. What is GitHub Pages?
GitHub Pages is a GitHub hosting service for publishing static websites from a repository. It serves files such as HTML, CSS and JavaScript.

## 2. Can you host dynamic apps here?
GitHub Pages cannot run server-side code such as PHP, Python or Node.js. A JavaScript front end that calls an external API can work, but the backend must be hosted elsewhere.

## 3. What are the limits of GitHub Pages?
It is designed for static sites, not server-side applications or databases, and has published build, bandwidth and site-size limits. Check GitHub's current documentation for the latest limits.

## 4. How do you update the website?
Edit the files, commit the changes and push them to the publishing branch (here, `main`). GitHub Pages republishes the site.

## 5. What happens when you delete the repo?
The Pages site is no longer served from that repository and becomes unavailable after GitHub processes the deletion.

## 6. What is the default file that loads?
`index.html` is the default entry page for a basic site root.

## 7. Can you use a custom domain?
Yes. Add the domain in repository Pages settings and configure the required DNS records with your domain provider.
