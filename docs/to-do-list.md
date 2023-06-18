# To-Do List

## Phase 1: End-of-Life the Old Site

- [x] Archive the current site's codebase.
  - [x] Clone the current site's codebase.
  - [x] Create a new remote repo.
  - [x] Force push the current codebase to the new remote.
  - [x] Archive the new remote.
- [x] Freeze the current site.
  - [x] Disable automatic CI in the `mikechurvis.github.io` repo.
  - [x] Put the current published site files on the `main` branch
  - [x] Change the GitHub Pages publisher target branch from `gh-pages` to `main`. 
  - [x] Republish the site.
  - [x] Verify that the current site remains published.
  - [x] Delete the `gh-pages` branch.
- [ ] Take down the API backend on DigitalOcean.
  - [ ] Shut down the droplet.

## Phase 2: Build the Placeholder for the New Site