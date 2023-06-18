# To-Do List

## Phase 1: End-of-Life the Old Site

- [x] Archive the current site's codebase.
  - [x] Clone the current site's codebase.
  - [x] Create a new remote repo.
  - [x] Force push the current codebase to the new remote.
  - [x] Archive the new remote.
- [x] Freeze the current site.
  - [x] Disable automatic CI in the `mikechurvis.github.io` repo, hereforward called the **"live site repo"**.
  - [x] Put the current published site files on the `main` branch
  - [x] Change the GitHub Pages publisher target branch from `gh-pages` to `main`. 
  - [x] Republish the site.
  - [x] Verify that the current site remains published.
  - [x] Delete the `gh-pages` branch.
- [x] Take down the API backend on DigitalOcean.
- [x] Purge old secrets from the live site repo.

The "current site" will hereforward be called the **"old site"**.

## Phase 2: Hand Over the live site repo from the old site to the new.

- [x] Make a new remote repo called `old`, hereforward called the **"old site repo"**.
- [x] Set the old site repo as a remote on the live site repo.
- [x] Push the live site repo's `main` branch to the old site repo.
- [x] Enable GitHub Pages on the old site repo's `main` branch.
- [x] Once the GitHub Pages CI job has completed its run, verify that the old site is available at `mikechurvis.com/old`.

## Phase 3: Build the Placeholder for the New Site

- [x] Show that the site is under construction.
  - [x] Initialize Astro.
  - [x] Make a giant box, center screen, that says "under construction".
  - [x] Put a link to the old site inside the box.
- [ ] Output the new site to the live site repo.