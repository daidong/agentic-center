# UD Center for Agentic Systems

Website for the Center for Agentic Systems at the University of Delaware, Department of Computer & Information Sciences.

**Live site:** [daidong.github.io/agentic-center](https://daidong.github.io/agentic-center/)

## Overview

A CIS-based research center focused on building, evaluating, and deploying dependable AI agent systems for science, infrastructure, and enterprise workflows.

## Development

This is a static HTML/CSS/JS site hosted on GitHub Pages. No build tools required.

To preview locally, open `index.html` in a browser, or use any local server:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

## Structure

```
├── index.html          # Main page
├── css/style.css       # Styles
├── js/main.js          # Minimal JS (nav, mobile menu)
├── images/             # Logos, screenshots, diagrams
└── README.md
```

## Updating Content

- **Team members:** Edit the `<!-- People -->` section in `index.html`. Copy a `.person-card` block and update name, initials, role, and link.
- **Research thrusts:** Edit `.thrust-card` blocks in the Research section.
- **News/updates:** Add entries to a News section when ready (template provided in comments).
- **Partners:** Add logos to `images/` and `<img>` tags to the Partners section.

## License

Content © University of Delaware. Site code is MIT-licensed.
