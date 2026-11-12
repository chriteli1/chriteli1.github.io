# chriteli1.github.io
Repo to host projects on GitHub Pages

## Update and deploy the latest game

In the repository's **Settings → Pages**, set the build and deployment source to **GitHub Actions**. Then run **Actions → Update submodule and deploy → Run workflow** on the default branch. The workflow updates `the_cursed_castle` to the latest `main` commit, commits that submodule pointer to the parent repository, and deploys the site.

The workflow fetches the submodule over HTTPS, so the submodule repository must be public.
