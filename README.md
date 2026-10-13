# ARISE HMS

ARISE HMS is a standalone HTML prototype. It has no build step or server-side
dependencies and can be deployed as a Netlify static site.

## GitHub repository

The public repository is [ARISE-HMS](https://github.com/lokeshvijayakumar0-dotcom/arise-hms).
Clone it with:

```powershell
git clone https://github.com/lokeshvijayakumar0-dotcom/arise-hms.git
```

## Deploy to Netlify

For the quickest deployment, sign in to [Netlify Drop](https://app.netlify.com/drop)
and drag this project folder onto the page. Netlify will publish `index.html`
without a build step.

For automatic deploys from GitHub, choose **Add new site → Import an existing
project**, select the repository, and deploy. The included `netlify.toml` sets
the publish directory to the project root. Future pushes to `main` will redeploy
the site.
