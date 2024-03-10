# JupyterLite Demo - CJ's copy

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://jupyterlite.github.io/demo)

JupyterLite deployed as a static site to GitHub Pages, for demo purposes.

## ✨ Try it in your browser ✨

➡️ **https://jupyterlite.github.io/demo**

![github-pages](https://user-images.githubusercontent.com/591645/120649478-18258400-c47d-11eb-80e5-185e52ff2702.gif)

![github-pages](https://cjwang.github.io/myJupyterLite/)

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+

## Deploy your JupyterLite website on GitHub Pages

Check out the guide on the JupyterLite documentation: https://jupyterlite.readthedocs.io/en/latest/quickstart/deploy.html

From the Actions tab on your repository, ensure that workflows are enabled. When you make a commit to the main branch, a Github Action will build your JupyterLite release and deploy it to the repository’s Github Pages. By default, the Github Pages site will be found at YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY-NAME. You can also check the URL from the Repository Settings tab Pages menu item.

If the deployment failed, go to “Settings - Actions - General”, in the “Workflow permissions” section, check “Read and write permissions”. Check that you have Github Pages enabled for your repository: from your repository Settings tab, select the Pages menu item and ensure that the source is set to GitHub Actions:

When you commit a file, an updated website will be built and published on Github Pages.

## Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- How-to Guides: https://jupyterlite.readthedocs.io/en/latest/howto/index.html
- Reference: https://jupyterlite.readthedocs.io/en/latest/reference/index.html
