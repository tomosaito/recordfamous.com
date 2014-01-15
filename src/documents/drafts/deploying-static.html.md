---
title: Simple static site using DocPad and GitHub 
layout: post
tags: ['node','post']
date: December 26 2013
---

Before we start make sure you have git and nodejs installed, go ahead and create a free github account and a username.github.com repository while you're at it.

Next you're going to install docpad globally.
`npm install -g docpad@6.59`

Now choose a skeleton, if you're familiar with HTML preprocessing, I recommend Bootstrap with Jade, otherwise the HTML5 Boilerplate works just fine. We're going to clone that repository.

```cd ~/workspace
git clone https://github.com/docpad/html5-boilerplate.docpad.git projectname & cd projectname
```

Next we'll install all the dependencies that Docpad needs to run
> npm install
