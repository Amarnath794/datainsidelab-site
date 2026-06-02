# DataInsideLab

A lightweight static website for publishing articles about data, AI, analytics, and technology news.

## Deploy on Vercel

This project does not need a paid server, database, or build command.

- Framework preset: `Other`
- Build command: leave empty
- Output directory: leave empty or use `.`
- Root directory: repository root

If Vercel shows `404: NOT_FOUND`, make sure the deployment points to the repository root that contains `index.html`.

## Domain

After deployment, add `datainsidelab.com` in Vercel Project Settings under Domains. Then update Namecheap DNS using the records Vercel shows.

## Add a new article

1. Create a new HTML file inside `articles/`.
2. Add the article card to `articles.html`.
3. If it should be featured on the homepage, add the card to `index.html`.
4. Add the URL to `sitemap.xml` and `rss.xml`.

## Add a new project

1. Create a new HTML file inside `projects/`.
2. Add a project card to `projects.html`.
3. Link the related GitHub repository, dashboard, screenshots, and main insights.
