# VerifyINEC

A free web tool that helps voters check whether an election link or message is genuine before they click, pay or share. Built for the #AI4Elections Hackathon (Electoral Cybersecurity track).

## What it does
- **Check a link:** flags lookalike INEC addresses, fake `.gov.ng` tricks, risky endings and other warning signs.
- **Check a message:** spots pressure tactics, requests for money or ID numbers, and fake rewards, including in Pidgin.
- **Registry:** separates INEC's real domains and subdomains (collected with [CYRECON](https://github.com/CYPHEM18)) from imitations.
- **Threat feed and report writer:** keeps flagged sites on your device and drafts takedown reports.

It checks authenticity only, never political content. It stores no personal data and runs entirely in the browser.

## Run locally
Open `index.html` in any browser. No build step.

## Deploy on Vercel
1. Push this repo to GitHub.
2. In Vercel choose **Add New Project** and import the repo.
3. Set **Framework Preset** to *Other*, leave the build command empty, and click **Deploy**.

## Limits
- A clean result never proves a site is official. Type known addresses yourself.
- The official list is a starter. Confirm domains with INEC's own channels.
- AI second opinion and claim verification need the server version (separate project with an API key). They do not run on a static host.

Not affiliated with INEC.
