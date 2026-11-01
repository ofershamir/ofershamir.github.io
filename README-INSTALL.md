# Academic website content assets

These files are designed as an overlay for the current Academic Pages template.

## Before copying

Commit your current local version so you can easily revert:

```bash
git add .
git commit -m "Checkpoint before adding site content"
```

## Copy into the repository

Copy the contents of this folder into the root of your Academic Pages project. Review conflicts before replacing existing files, especially `_data/navigation.yml` and `_pages/about.md`.

## Required manual steps

1. Merge `CONFIG-SNIPPET.yml` into the existing `_config.yml`.
2. Add your profile photo as `images/profile.jpg`.
3. Add the final shared banner as `assets/images/turbulence-sphere-banner.jpg`.
4. Follow `BANNER-INSTALLATION.md`.
5. Replace the four research placeholders in `assets/images/` with real figures.
6. Add the current CV as `files/Ofer_Shamir_CV.pdf`.
7. Add current email, affiliation, Google Scholar, ORCID, and GitHub links.
8. Check whether the remaining in-preparation manuscript is distinct from the published 2026 GRL paper.

## Local preview

From the root of the Academic Pages repository:

```bash
docker compose up
```

Open `http://localhost:4000`.

## Important content assumption

The Publications page currently has one item under In preparation and no Submitted section. The older title `A Stochastic Null Hypothesis for the Tropical Variability of Outgoing Longwave Radiation` was omitted because it may have developed into the published 2026 GRL paper. Restore it only if it is a distinct manuscript.
