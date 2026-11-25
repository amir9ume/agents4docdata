# Agents4DocData at COLING 2027

Static, single-page website for the draft joint DocAgents and AgentDM call for papers.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Draft safeguard

The page currently:

- displays a visible working-draft notice;
- labels organizer decisions as internal working notes; and
- includes `<meta name="robots" content="noindex, nofollow">`.

Before announcing the official call, update the dates and submission details, remove the internal organizer section if appropriate, change the draft labels, and remove the `robots` meta tag.

## Hosting

This directory can be deployed without a build step to AWS Amplify Hosting, GitHub Pages, Netlify, Cloudflare Pages, or any standard static web host.

For a manual AWS Amplify deployment, upload `agents4docdata_coling2027.zip` in the Amplify console. For a maintainable production site, connect the directory to a Git repository so updates deploy automatically.
