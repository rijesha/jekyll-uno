---
layout: post
title: Ooh I made a blog
date: 2017-09-25 21:32:00 -0700
description: How to set up a website and blog with GitHub pages
img: websiteScreenshot.PNG # Add image post (optional)
tags: [Jekyll, GitHub Pages] # add tag
---

So this is my first post on this blog. Hopefully, it will be filled with some interesting subject matter. The following is mostly a poorly worded reference for myself, but could also help you set up a similar site. 

### Setting Up the Splash Page

The splash homepage (found at [rijesha.com](rijesha.com)) is based on a template from [html5up.net](https://html5up.net/). html5up.net produces free responsive html5 themes. A responsive website changes for different devices and screen sizes. A few modifications were made to the original template, particularly the Javascript, to allow for a dynamic "about me" section. Check out the original [here](https://html5up.net/identity).

### Enabling GitHub pages

The website was then pushed to a GitHub repo with the name [rijesha.github.io](https://github.com/rijesha/rijesha.github.io). This is the default name that is required for the base GitHub pages site. In addition, you may need to set up DNS name forwarding. There are plenty of instructions for this floating around the internet. [GitHub Instructions](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)

### Setting up the blog site

GitHub pages allow for the creation of [project pages](https://help.github.com/articles/user-organization-and-project-pages/). This is a convenient way to generate a subsite while keeping all the [files separate](https://github.com/rijesha/blog). The subrepository is based on a [jekyll theme](http://artemsheludko.pw/flexible-jekyll/). [Raw blog posts](https://github.com/rijesha/blog/tree/master/_posts) are written in markup and are generated after being uploaded to GitHub. Finally, in the repository settings you will [need to enable githubpages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/).