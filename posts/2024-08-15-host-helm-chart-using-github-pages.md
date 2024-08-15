Host Helm Chart repository using github pages
=
# Overview
We are going to use the [`helm/chart-releaser-action`](https://github.com/helm/chart-releaser-action) to manage a helm chart repoistory. 

# Setup Helm Chart Repository
## Create a new repository
1. Create a new repository under your GitHub account, with the name `helm-charts`
## Enable GitHub Page
1. Create a branch named `gh-pages` in GitHub repository `helm-charts`
1. Create a folder `/charts` in `gh-pages` branch.
1. Enable the GitHub Page for this new repository &rarr; `Settings` &rarr; `Pages`:
   * Set `Source` to `Deploy from a branch`
   * Set `Branch` to `gh-pages` served from on `/(root)`
   ![GitHub Page Settings](pic/github-page-settings-for-helm-chart-hosting.png)
