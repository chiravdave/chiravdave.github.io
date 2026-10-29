# Agent context

## Site overview

- This repository is Chirav Dave’s personal portfolio, published as a static GitHub Pages site at `chiravdave.github.io`.
- Keep it as a single static page. All portfolio copy and sections belong in `index.html`; styling is in `css/style.css`.
- Use relative asset paths such as `./css/style.css` and `./images/...` so assets work locally and on GitHub Pages.
- The site does not require Jekyll, a build step, or production dependencies. Do not add a framework or dependencies without asking first.

## Content and design direction

- Present Chirav as an experienced AI/ML systems architect with understated entrepreneurial ambition. Do not imply that he has founded a company.
- His positioning spans model post-training and fine-tuning through production AI systems, including AI Firewall and AI Gateway work at A10 Networks. Keep product descriptions high-level and grounded in supplied facts.
- Keep the clean, minimal editorial design, responsive layouts, and accessible navigation.
- The main sections are Hero, About, Projects & Open Source, Writing, and Contact. Keep section comments in `index.html` and grouped comments in `css/style.css` clear and useful.
- Project cards are in the `#work` section of `index.html`, inside `.project-grid`. Use two columns on desktop and one on mobile. Add each project as an `article.project-card`; keep single or odd final cards centered at a limited width.
- Add new Medium articles at the top of `.writing-list`. CSS counters generate the visible numbers, so do not hard-code article numbers.

## Working preferences

- Do not run commands other than reading files unless the user asks first. Do not add or run tests unless requested.
- Ask before adding production dependencies.
- Summarize code changes in `CHANGELOG.md`.
