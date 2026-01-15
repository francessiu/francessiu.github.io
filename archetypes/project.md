---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
technologies: ["PyTorch", "CUDA", "SYCL"]
category: "HPC" # e.g., HPC, Data Science, Full Stack
duration: ""
github: "https://github.com/francessiu/{{ replace .Name "-" "" }}"
live_demo: "" # Optional link to a live version
---

## Project Overview

## Technical Deep Dive

## Results & Impact

{{< github_link >}}