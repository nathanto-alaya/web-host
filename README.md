# Alaya webinar hub

Internal working documents for the 27 October webinar.

## What is in here

| File | What it is |
|---|---|
| `index.html` | The 3 structures, in full, plus links to everything below |
| `email-sequence.html` | 16 campaign emails, written in full |
| `story-bank.html` | Real client stories with sources and freshness flags |
| `ads-brief.html` | Timeline, budget questions, paid versus free |
| `workshop-playbook.html` | How to build a session that sells, and where our plan falls short |

Every file is self contained. No build step, no dependencies. Fonts load from Google Fonts, everything else is inline.

## Publishing on GitHub Pages

1. Settings, then Pages
2. Source: Deploy from a branch
3. Branch: `main`, folder: `/ (root)`, then Save
4. Wait 1 to 2 minutes for the first build

The `.nojekyll` file stops GitHub from running Jekyll over the folder.

## Updating

Replace a file and commit. The site rebuilds automatically within a minute or two.

## Before you make this repo public

These pages contain pricing decisions, campaign budgets and internal commentary. On the GitHub free plan, Pages only publishes from a public repository, which means anyone with the URL can read them.

Options if that is not acceptable:

- Keep the repo private and share the HTML files as email attachments instead
- Use Cloudflare Pages with Cloudflare Access, which puts the site behind a login and is free for up to 50 users
- Upgrade the GitHub plan, which allows Pages from a private repo

Every page carries a `noindex, nofollow` tag, which keeps it out of search results. It does not stop anyone who has the link.
