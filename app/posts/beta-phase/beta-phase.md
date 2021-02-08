---
tags: false
layout: collection
title: Beta phase
pagination:
  data: collections.beta-phase
  reverse: true
  size: 50
permalink: "beta-phase/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---
