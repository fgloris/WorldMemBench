# WorldMemBench

WorldMemBench is a benchmark platform to evaluate the memory capabilities of learned world models. This repository contains the documentation website (Jekyll) and the specification pages for the benchmark. The dataset and evaluation code will be linked from this repository when released.

## What I added

- Jekyll site configuration: `_config.yml`
- Layout and pages: `_layouts/default.html`, `_pages/paper.md`, `_pages/about.md`, `_pages/dataset.md`
- Styling: `assets/css/style.scss`
- Bundler: `Gemfile`
- Updated `index.html` to be a Jekyll home page

## Run locally (Windows PowerShell)

Install Ruby and Bundler if you don't have them. On Windows, we recommend RubyInstaller (https://rubyinstaller.org/) and installing the MSYS2 toolchain when prompted.

From PowerShell, in this repository root:

```powershell
gem install bundler
bundle install
bundle exec jekyll serve --livereload
```

Open `http://127.0.0.1:4000/` in your browser to view the site.

If you prefer GitHub Pages hosting, this repository is ready to be served by GitHub Pages using the `github-pages` gem (no additional CI required). Push to the `main` branch and enable GitHub Pages in the repository settings.

## Next steps

- Add dataset files and link downloadable assets from the `dataset` page
- Add evaluation scripts and baseline code (Python or PyTorch recommended)
- Add license and contributor instructions
