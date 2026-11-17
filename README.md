# pa-site

The public home page and privacy policy for Personal Assistant, a private, single-user tool that reads its owner's Gmail and Google Calendar and emails its owner a morning brief. Live at **https://pa.samueltait.com**.

Google's OAuth consent screen needs a public home page and privacy policy for the app, on a domain the owner controls. That is all this site is for. There is no app, sign-up or service here.

The tool itself lives in a separate private repo, `personal-assistant`.

## What's here

| File | What it is |
|---|---|
| `index.html` | Home page: what the tool is and who uses it |
| `privacy.html` | Privacy policy and terms, written to Google's API Services User Data Policy (Limited Use) |
| `style.css` | The only stylesheet; no scripts, trackers or third-party assets |
| `CNAME` | Custom domain for GitHub Pages |
| `_config.yml` | Keeps the repo docs (this README, `CLAUDE.md`, `AGENTS.md`) off the published site |

## How it's served

GitHub Pages builds from `main` at the root, with HTTPS enforced and the custom domain in `CNAME`. A push to `main` is live within a minute or two. Don't delete `CNAME`: Pages drops the custom domain and the OAuth consent screen links break.

## Keeping it accurate

The privacy page is a promise to Google and to anyone reading it. It must match what Personal Assistant actually does.

- Change the page **before** adding a Google scope, a new kind of access (for example creating drafts), a new data processor, or storage anywhere other than the owner's own computer.
- Update "last updated" in `privacy.html` whenever the substance changes.
- Keep the Google consent screen's home page and privacy URLs pointing here.

## Contact

The contact address is in the footer of both pages.
