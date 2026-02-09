# whist-score
Whist Score Keeper

## Deploy to Cloudflare Workers

This repository now includes a GitHub Actions workflow at `.github/workflows/deploy-workers.yml`.

### Required GitHub repository secrets

- `CLOUDFLARE_API_TOKEN`: API token with Workers Scripts Edit permissions
- `CLOUDFLARE_ACCOUNT_ID`: Your Cloudflare account ID

### Deploy trigger

- Automatic deploy on push to `main`
- Manual deploy from the Actions tab (`workflow_dispatch`)
