---
layout: blog.njk
title: Artigos
date: 2024-08-29
pagination:
  data: collections.post
  size: 20
permalink: "blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html"
metaDescription: A sample Blog page listing various posts.
subtitle: A collection of technical blog posts and random thoughts
eleventyNavigation:
  key: Blog
  order: 2
---
