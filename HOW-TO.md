# Listing Homer on DefiLlama: two pull requests

## 1. TVL: DefiLlama-Adapters
1. Open https://github.com/DefiLlama/DefiLlama-Adapters and press **Fork**.
2. In your fork, go to the `projects` folder, then **Add file → Upload files**.
   Upload the folder `1-DefiLlama-Adapters/projects/homer` (the file must end up at `projects/homer/index.js`).
3. Commit, then **Contribute → Open pull request**.
   Title: `Add Homer (Elysium)`. Paste `1-DefiLlama-Adapters/PR-description.md` as the description and attach `homer-logo-1000.png`.
4. Tick **"Allow edits by maintainers"**.

## 2. Fees and volume: dimension-adapters
1. Fork https://github.com/DefiLlama/dimension-adapters.
2. Upload `fees/homer/index.ts` and `aggregators/homer-swap/index.ts` (keep those exact paths).
3. Open the pull request with `2-dimension-adapters/PR-description.md`, add the link to PR 1, and tick "Allow edits by maintainers".

Don't add or change any other files (no package-lock or pnpm-lock).
After the merge it can take up to a day to appear on DefiLlama.
