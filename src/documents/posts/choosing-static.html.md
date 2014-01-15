---
title: Choosing static site builders with open frameworks
layout: post
tags: ['node','post']
date: December 26 2013
---

I've been building dynamic sites with PHP for a while and big or small, I've used some combination of CMS and Modules, piecing together content types, views and templates. The strength of the PHP community has meant I've rarely had to spend dev hours building something from scratch. PayPal, Instagram API or WYSIWIG, there's a module for it.

Recently, I've been diving into NodeJS and was amazed at the products built with it. While I appreciate GUIs, I miss the immediacy of templating and desiging in code. Maybe it's the hipster minimalist in me but there's something raw and cool about rendering and serving static sites on a github pages.

There are a few JS based static site builders that I've come across, [Docpad](http://docpad.org/), [Hexo](http://zespia.tw/hexo/), [Assemble.io](http://assemble.io/), [Blacksmith](http://blacksmith.jit.su/) & [Wintersmith.io](http://wintersmith.io/). Most are inspired by their Ruby counterparts, [Jekyll](http://jekyllrb.com/) & [Octopress](http://octopress.org/), and function essentially the same, with Eco, Jade or EJS templating and MD source posts.

I'd started with Hexo, the quickest to deploy with great documentation and a few themes. Though I quickly moved to Docpad for the robustness, modules and community support. I'm curious how far the templating and preprocessing could go towards using DocPad with Github as Content Management and Angular & Firebase for app functionality. I'm excited to find out.

I'll post a walkthrough next to introduce you to the kitchen sink of static site building.