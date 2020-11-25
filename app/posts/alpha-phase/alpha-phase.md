---
tags: false
layout: collection
title: Alpha phase
pagination:
  data: collections.alpha-phase
  reverse: true
  size: 50
permalink: "alpha-phase/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---
