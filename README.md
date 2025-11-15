# blog

`blog` is a bilingual Jekyll site that uses Minimal Mistakes as a foundation, extended with the collection of Jekyll plugins defined in this repository.
It builds through GitHub Actions for CI/CD and is published via GitHub Pages, so every push to `main` runs the workflow that installs the gems, builds the site, and deploys it automatically.

## Tech stack

- **Jekyll + Minimal Mistakes** – the static site generator and theme powering the layout, navigation, and content structure.
- **Plugins** – additional Jekyll plugins in this repo add functionality like bilingual content handling, pagination, and asset management.
- **GitHub Actions** – the workflow installs dependencies, runs the build, and pushes the generated `_site` to GitHub Pages for deployment.
- **GitHub Pages** – serves the generated site at the configured domain.

## Local setup

1. Install Ruby dependencies listed in `Gemfile` with Bundler:

   ```bash
   bundle install
   ```

2. Run the Jekyll development server with live reload:

   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://127.0.0.1:4000` (or the address shown in the console) to preview the bilingual blog locally.

## Notes

- Keep the translation strings and bilingual navigation in sync; the `_config.yml` and `_data` folders contain the localized content.
- The GitHub Actions workflow is triggered on pushes and pull requests to `main`; customizing it lets you run tests, linting, or other checks before deployment.
- Because GitHub Pages builds the `_site` folder, avoid committing generated files unless you intend to override the deployment step.

## Adding content

- **Pages**: Add new Markdown files to `_pages/en` or `_pages/de` and include a front matter with `layout: page` and the appropriate `lang` value; the shared layouts automatically localize navigation and metadata.
- **Posts**: Create files in `_posts/en` or `_posts/de` named with the Jekyll date-title format (e.g., `2024-05-01-topic.md`) and set `lang` plus any collection tags you need—ensuring plug-in logic keeps metadata consistent.

## Custom UI helpers

- `_includes` contains helpers that toggle between dark/light mode as well as the language switcher; dark mode and English are the default states, but the code responds to user preference and the current page lang.
- `_layouts` has custom localization handling so shared parts like headers, footers, and metadata display the right language strings as you switch between `en` and `de`, while still honoring theme defaults.
