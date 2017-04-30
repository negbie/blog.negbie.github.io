---
title: Hugo blog with RStudio, GitKraken and Netlify
author: negbie
date: '2017-04-30'
slug: hugo-blog-with-rstudio-gitkraken-and-netlify
categories:
  - deployment
  - blog
tags:
  - hugo
  - rstudio
  - git
  - gitkraken
  - netlify
---

# Choosing a static site generator

I was looking for something with which I can save some notes online and publish them. First I tried discourse as a well searchable knowledgebase. It was quite nice and you can get it running in a few minutes as a DigitalOcean droplet or docker container. But I'm not familiar with ruby and have to maintain still another os. After some time I came across static site generators.

First I tried hubpress which was to laggy for me. Jekyll and Octopress are written in ruby. Despite the fact you don't need to know ruby to use Jekyll I feel more comfortable not to use a blackbox. Since I'm currently learning Go I decided to give Hugo a try. I spent some time to google for blogs which were created with Hugo.

I stumpled upon the blog post ["Making a Website Using Blogdown, Hugo, and GitHub pages"](https://proquestionasker.github.io/blog/Making_Site/) from Thomas Amber. The possibility to embed R code was quite interesting so I decided to give it a try. I won't explain the steps as detailed as Thomas did but as short as possible.

# Install Hugo with Blogdown in RStudio




