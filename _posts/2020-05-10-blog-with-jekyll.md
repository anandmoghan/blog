---
layout: post
title:  "Blog with Jekyll: Firebase Hosting and GitHub CI"
date:   2020-05-10 16:00:00 +0530
permalink: /posts/:year/:month/:day/:title:output_ext
categories: setup jekyll firebase github-ci
---

I am setting up a blog which used [Jekyll](https://jekyllrb.com) as static page generator, [Firebase](https://firebase.google.com) as hosting provider and [GitHub CI](https://help.github.com/en/actions/building-and-testing-code-with-continuous-integration) to enable continuous integration to publish content.

You need a basic understanding of [markdown](https://guides.github.com/features/mastering-markdown) to write content.

### Jekyll Installation

```
gem install bundler jekyll jekyll-watch
jekyll new my_blog
jekyll serve
```
