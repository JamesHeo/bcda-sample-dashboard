# BCDA Sample Data Dashboard Deploy

This folder is ready to deploy as a static website.

## Files

- `index.html`: self-contained dashboard with embedded sample data
- `.nojekyll`: keeps GitHub Pages from applying Jekyll processing

## Recommended Deployment Options

### Private team access

Use Vercel or Cloudflare Pages with access protection if this dashboard may contain real or sensitive healthcare data.

### Public sample/demo access

Use GitHub Pages if this is strictly sandbox/sample data and can be public.

## GitHub Pages Quick Path

1. Create a new GitHub repository.
2. Push the contents of this `deploy` folder.
3. In GitHub, open repository Settings > Pages.
4. Set the publishing source to the main branch root.
5. Share the GitHub Pages URL with the team.

## Safety Note

Do not deploy real BCDA beneficiary data or PHI to a public URL.
