# Portfolio

A portfolio and blog page build with static site generator [Hugo](https://gohugo.io/about/what-is-hugo/) using [Congo theme](https://themes.gohugo.io/themes/congo/).

[![Super-Linter](https://github.com/philipplewe/portfolio/actions/workflows/linter/badge.svg)](https://github.com/marketplace/actions/super-linter)

## Pre-requisites

* Hugo CLI

### Hugo CLI installation on macOS

```bash
brew install hugo
```

## Local development

To render the site locally including draft contents, run hugo server with the `--buildDrafts` or `-D` parameter:

```bash
hugo server --buildDrafts
```

The site is accessible via the browser on [http://localhost:1313/](http://localhost:1313/) and supports [LiveReload](https://gohugo.io/getting-started/usage/#livereload).

When editing content, if you want your browser to automatically redirect to the page you last modified, run:

```bash
hugo server --navigateToChanged
``````

## Deployment to Github pages

On every push to `main` branch the site is build and deployed to Github pages. See [.github/workflows/hugo.yaml](.github/workflows/hugo.yaml) for deployment process details.

The published page is available at [https://philipplewe.github.io/portfolio/](https://philipplewe.github.io/portfolio/).

## References

* Hugo
  * [Hugo Documentation](https://gohugo.io/documentation/)
  * [CLI installation on macOS](https://gohugo.io/installation/macos/)
  * [Hosting and Deployment on GitHub Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
* Congo
  * [Congo Theme documentation](https://jpanther.github.io/congo/docs/)
  * [Update Congo theme installed as git submodule](https://jpanther.github.io/congo/docs/installation/#update-using-git)