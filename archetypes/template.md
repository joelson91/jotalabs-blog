---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
draft: false
tags: # ["first"]
description: "Desc Text."
cover:
    image: "images/"
    alt: "<alt text>"
    caption: "<text>"
    relative: false
---