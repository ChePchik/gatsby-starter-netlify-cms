---
layout: blog
title: "How to make sandwiches like a pro"
date: 2020-09-26 11:59:59
thumbnail: "/images/sandwich.jpg"
---

Съешь ещё этих мягких французских булок, да выпей же чаю.

collections:

- name: "blog"
  label: "Blog"
  folder: "content/blog"
  create: true
  slug: "{{year}}-{{month}}-{{day}}-{{slug}}"
  fields:
  - {label: "Layout", name: "layout", widget: "hidden", default: "blog"}
  - {label: "Title", name: "title", widget: "string"}
  - {label: "Publish Date", name: "date", widget: "datetime"}
  - {label: "Body", name: "body", widget: "markdown"}
