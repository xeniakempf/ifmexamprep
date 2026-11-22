# IFM Exam Prep

One repo, two Netlify sites.

| Folder | Domain | What it is | Netlify base directory |
|---|---|---|---|
| `site/` | ifmexamprep.com | Marketing site + waitlist (Netlify Forms) | `site` |
| `app/`  | ifmexamprep.app | Practice-question app (prototype) | `app` |

Each folder has its own `netlify.toml`. A push only redeploys the site whose folder changed.

## Netlify setup (once per site)
1. Add new site → Import from Git → pick this repo.
2. Base directory: `site` (or `app`). Build command: blank. Publish directory: `.`
3. Domain management → add the custom domain.

## Waitlist
Signups appear under the `site` project → Forms → `waitlist`. Turn on form detection and add an email notification there.
