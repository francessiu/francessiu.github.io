---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author: "Frances Siu"
description: ""
tags: ["Statistics", "Machine Learning", "Python", "C/C++"]
categories: ["Data Science", "Software Development", "Philosophy"]
keywords: ["data analysis", "high performance computing", "UoE"]
canonicalURL: "" # IMPORTANT for syndication. Set this to the published URL.
image: "/images/post-{{ replace .Name "-" "_" }}.jpg" # Featured image path
---