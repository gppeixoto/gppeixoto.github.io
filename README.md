# gppeixoto.com

A minimal Hugo profile and blog site.

## Preview locally

Install [Hugo extended](https://gohugo.io/installation/):

```sh
brew install hugo
```

Then run:

```sh
hugo server
```

Open the local URL Hugo prints (usually `http://localhost:1313`).

## Write a blog post

```sh
hugo new content blog/my-post.md
```

Set its title and date, then write Markdown below the front matter. Posts publish at `/blog/my-post/`.

## Deploy

1. Create the GitHub repository `gppeixoto/gppeixoto.github.io` and push this project to its `main` branch.
2. In **Settings → Pages**, select **GitHub Actions** as the source.
3. In **Settings → Pages → Custom domain**, enter `gppeixoto.com`. The included `static/CNAME` also identifies the domain in the deployed site.
4. At Namecheap, point the apex (`@`) to GitHub Pages' four A records, and point `www` to `gppeixoto.github.io` with a CNAME. Follow GitHub's current [custom-domain instructions](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site) for the exact records and verification steps.

Pushing to `main` deploys the site.
