# Workflow

This repo covers the public portfolio workflow for Claw Prints.

## Canonical flow
1. the team decides a milestone, lesson, or project belongs in the portfolio
2. content is updated in `data/content.json`
3. structural/presentation changes are made in `index.html` only when needed
4. changes are reviewed before publish
5. the repo is pushed and the static site is redeployed

## Repo usage
### Use this repo for
- public portfolio content
- public milestone summaries
- presentation changes for the static site
- deployment notes for the portfolio site

### Do not use this repo for
- private memory or internal-only operating notes
- HQ workflow rules that belong in `depth-ops`
- unrelated application code

## Update rules
- prefer content edits in `data/content.json`
- keep deployment instructions current in `DEPLOY.md`
- document durable product/workflow expectations in `docs/`
