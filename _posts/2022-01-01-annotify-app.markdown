---
layout: post
title:  "Git-Centric Sci Ops Workflow"
date:   2022-11-28 4:30:00
categories: architecture
---


At first, it is just a matter of  exploration ... and then later, it will always be a matter of exploration ... ***we get better by learning from how others are learning.*** 

This means that our "app" or learning and research toolchain will be constructed using a dogfooding approach

We cannot emphasize the dogfooding nature of enough ... the Sci Ops knowledge graph project might eventually mature into a community project ... but at first, it's just us dogfooding a toolchain and contributing to open source projects.

We would expect that we are not alone in this ... we see research scientists [or their grad assistant Ph. D. candidates] developing their own SciOps workflow will rely upon dogfooding some sort of some-established, but still evolving and improving CI/CD process for Sci Ops ... of course that means fully drinking the Kool-Aid on [continuous integration, continuous delivery, and continuous deployment architectures](https://learning.oreilly.com/library/view/grokking-continuous-delivery/9781617298257/) ... with some sort of fluid, evolving Sci Ops [knowledge graph analytic](https://learning.oreilly.com/library/view/building-knowledge-graphs/9781098127091/ch02.html) [data engineering lifecycle](https://learning.oreilly.com/library/view/fundamentals-of-data/9781098108298/ch02.html).  


We are not interested in re-inventing any wheels ... this is all about simplifying reuse ... a such, it will involve different, now well-established or common methods, such as:

* Git, GitHub Actions/Codespaces, [GitLab CI/CD](https://docs.gitlab.com/ee/topics/gitlab_flow.html), Gerrit code review and perhaps some sort a light-weight front-end like [Lit.dev]/(http://lit.dev)

* containers, virtual environments, protected spaces like FreeBSD jails or Fedora toolboxes, Podman, Docker, K8s ... it's all about sharability and reproducibility

* Various package management architectures ... such as [Conda package mgmt](https://docs.conda.io/en/latest/), FlatPak, RPEL, dnf, yum, apt, apk pip ... reproducibility, reproducibility, reproducibility

* A [Pythonic data exploration infrastructure](https://github.com/jakevdp/PythonDataScienceHandbook) including the [Jupyter architecture](https://docs.jupyter.org/en/latest/projects/architecture/content-architecture.html) and the [standard .ipynb JSON notebook schema](https://github.com/jupyter/nbformat), [SnakeMake workflow mgmt system](https://snakemake.readthedocs.io/en/stable/), as well as others, like [Google Colaboratory](https://colab.research.google.com/) or [Amazon EMR JupyterHub](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-jupyterhub.html) or others which use a similar, ***nearly*** standard architecture.


* Rentable BigCompute