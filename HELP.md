# Help Me!

## Quick Start Guide

+ Start here [Creating GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)
+ Then read [Adding content](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll)
+ and eventually [Testing locally](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)
    + `bundle exec jekyll serve --open-url --livereload`
    + to serve from root on local machine add `--baseurl=""`

> [!NOTE]
> If you've installed Ruby 3.0 or later (which you may have if you installed the default version via
> Homebrew), you might get an error at this step. That's because these versions of Ruby no longer
> come > with webrick installed.

> [!TIP]
> To fix the error, run `bundle add webrick`, then re-running `bundle exec jekyll serve`.

> Jekyll is an active open source project that is updated frequently. If the github-pages gem on
> your computer is out of date with the github-pages gem on the GitHub Pages server, your site may
> look different when built locally than when published on GitHub.

To avoid this, regularly update the github-pages gem on your computer by running
`bundle update github-pages` (or ~~`gem update github-pages`~~ without Bundler installed)

## Excluding and Including Files

By default, Jekyll doesn't build files or folders that:
+ are located in a folder called /node_modules or /vendor
+ start with _, ., or #
+ end with ~
+ are excluded by the exclude setting in your configuration file

If you want Jekyll to process any of these files, you can use the include setting in your configuration file.

## Dependencies

+ [Dependency versions](https://pages.github.com/versions/)

## Try 

[Font awesome Jekyll plugin](https://github.com/drewish/jekyll-font-awesome-sass)
