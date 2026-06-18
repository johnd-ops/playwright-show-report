# playwright-show-report

Hosted Playwright HTML reports for PlaySpace E2E runs.

Populated automatically by `.github/workflows/e2e-staging.yml` in
PlaySpace-Engineering/PlayspacePlatform — every failed staging E2E run
publishes its `playwright-report/` directory under `/<commit-sha>/` on
this repo, served via GitHub Pages at
https://johnd-ops.github.io/playwright-show-report/

Failure messages posted to Slack `#qa-e2e` link directly into this
host. Not intended for manual editing.
