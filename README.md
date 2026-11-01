# ai-maestro.23blocks.com redirects

The old AI Maestro site lived at ai-maestro.23blocks.com. It is now two sites:

- https://getaimaestro.com, the marketing site (home, iPhone, vision, ecosystem, experiments, blog)
- https://aimaestro.sh, install and docs

Each old page here is a stub that redirects to the same page on its new site (meta refresh, `rel=canonical`, a script that keeps the `#fragment`, and a visible link). Any other path gets `404.html`, which redirects to https://getaimaestro.com/. GitHub Pages serves `main` at `/`; `CNAME` holds the old domain.
