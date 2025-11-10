# Stop Killing YouTube — Protest Site

A minimal, focused site calling for fairer moderation, transparent appeals, and better ad safety on YouTube.

Preview
- Open the site locally: 
  - Quick: open `src/index.html` in your browser.
  - Recommended (serves files over HTTP):  
    `cd src && python3 -m http.server 8000`  
    then visit `http://localhost:8000`

What this repo is for
- Host the manifesto and resources.
- Collect real creator/ viewer experiences and examples of problematic moderation.
- Provide simple, shareable calls-to-action people can use.

How to contribute
1. Fork the repo and create a branch.
2. Add your experience or story as a new markdown file in `content/experiences/` (create the folder if it doesn't exist). Use the template below.
3. Optionally update the site copy or assets in `src/`.
4. Create a pull request describing your change.

Experience/Story template (save as `content/experiences/your-name.md`):
```md
---
title: "Short descriptive title"
date: 2025-11-10
location: "optional, e.g. country or platform"
---

Tell your story in a few paragraphs. Include dates, public links (if any), and what outcome you'd like to see.
```

Pull request guidelines
- Keep content factual and respectful.
- Do not include personally identifiable information of third parties without consent.
- Prefer links to public sources (articles, tweets, threads, archives) when possible.

Share the site
- Share the URL or a hosted deploy (GitHub Pages or similar).
- Encourage others to submit PRs with their experiences and to amplify creators affected by unfair moderation.

Legal / content note
- By contributing you confirm you have the right to share the content you submit.
- This project is a peaceful advocacy resource — avoid doxxing, threats, or calls for harassment.

If you want, I can:
- add a CONTRIBUTING.md,
- scaffold `content/experiences/` and add a sample entry,
- or create a GitHub Pages workflow to publish `src/` automatically.