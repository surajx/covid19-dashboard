# Contributing To This Project

We highly encourage contributions to this project and welcome PRs.

Familiarity with [fastpages](https://github.com/fastai/fastpages) is helpful.  All you need to do is include the appropriate front matter in your notebook.  See [this guide](https://github.com/fastai/fastpages#customizing-blog-posts-with-front-matter). 

**A good pull request to emulate is [this one](https://github.com/github/covid19-dashboard/pull/33)** - study the Jupyter notebook closely, especially the first cell that specifies the metadata, and how cells are hidden with `#hide` or `#hide_input`.

You should preview your dashboard locally by following [the Development Guide](https://github.com/fastai/fastpages/blob/master/_fastpages_docs/DEVELOPMENT.md), before submitting a PR.

# Guildelines For New Dashboards

- Your dashboard should not duplicate or present substantially the same information to what already exists in other dashboards.
- Any technical information and notes should go in an appendix.
- Make the visualization as approachable as possible.  Explain things in plain english.  Font sizes should be easy to read.  
- Keep the content of the dashboard scoped to one logical subject or theme.  
- If there are too many charts, we may ask you to provide a mechanism to allow readers to more easily search for the information they need.  Here is [an example](https://covid19dashboards.com/growth-bayes/) of using a dropdown list to allow readers to select the country they are interested in.
- Put your main visualization at the top of your notebook.  The methodology or "how to" should either be in footnotes or hidden from view.

We cannot guarantee that we will accept every submission to this project, but we are happy to work with you as much as possible.
