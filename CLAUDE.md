# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

A two-page static site (`index.html`, `privacy.html`, `style.css`) served by GitHub Pages at https://pa.samueltait.com. It exists so the Google OAuth consent screen for the private `personal-assistant` tool has a public home page and privacy policy. This repo is **public**.

## Rules

- The privacy page must describe exactly what `personal-assistant` does with Google data. If a change to that tool adds a scope, a new kind of access (drafts, labels, sending to anyone but the owner), a new processor or off-machine storage, update `privacy.html` and its "last updated" date first, and say so.
- Never remove `CNAME`; Pages would drop the custom domain.
- Plain HTML and CSS only: no JavaScript, analytics, fonts or other third-party requests.
- Public repo: no hostnames, IP addresses, internal paths, tokens or anything about the owner beyond what the pages already say.
- No em dashes in copy. Australian English.
- Commit or push only when asked; a push to `main` is live in about a minute.
