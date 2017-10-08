---
title: 'Brew: excluding packages from upgrade'
layout: Post
date: 2017-10-08T06:58:37.643Z
categories:
  - Homebrew
tags:
  - postgresql
---
If you have some projects that depend on a particular version of package then a simple way to upgrade everything that doesn't have a dependencie is to pin the items that do and upgrade the rest.

The following would pin posgresql to it's current version and then upgrade everything else.

`$ brew pin postgresql`

`$ brew upgrade`
