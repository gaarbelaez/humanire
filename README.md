# HUMANIRE — project website

Simple Jekyll site intended for deployment on GitHub Pages.

## Local preview

Install Ruby/Jekyll or use GitHub's Pages environment, then:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## GitHub Pages

1. Create a repository, for example `humanire.github.io`.
2. Copy the contents of this directory into the repository.
3. Push to GitHub.
4. In **Settings → Pages**, select **GitHub Actions** or the appropriate Pages deployment method.
5. Add the final project URL to `_config.yml`.

## Content policy

This public version intentionally excludes:
- project budget and detailed financial information;
- internal risk-management details;
- detailed personnel allocation and recruitment information;
- confidential industrial information;
- detailed internal planning and proposal-only material.

Before publication, replace or verify:
- official ANR acknowledgement/logo;
- institutional partner logos;
- public contact address;
- final project start date;
- links to institutional project pages;
- publication and output links.

## Suggested maintenance workflow

- Add a new Markdown file under `_posts/` for each project news item.
- Update `publications.md` when a paper/output becomes public.
- Keep partner descriptions short and public-facing.
