# My First Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alisonmitchell/my-first-binder/master)

## Introduction
A presentation entitled *Reproducible Research: An Introduction to The Turing Way and Binder* given by The Alan Turing Institute (the UK's national institute for data science and artificial intelligence) introduced the audience to *The Turing Way* and Project Binder, and was followed by the Zero-to-Binder tutorial.

## The Turing Way
Reproducible research is necessary to ensure that scientific work can be trusted. Funders and publishers are beginning to require that publications include access to the underlying data and the analysis code. The goal is to ensure that all results can be independently verified and built upon in future work. [*The Turing Way*](https://github.com/alan-turing-institute/the-turing-way) is a how-to guide for reproducible data science.

## Project Binder
One tool *The Turing Way* recommends using is [Project Binder](https://jupyter.org/binder).

* [Binder](https://mybinder.readthedocs.io/en/latest/) is the user interface/experience which allows you to create custom computing environments that can be shared and used by many remote users. A Binder is a Git repository that has been outfitted with the appropriate build files so that its content can be connected with a BinderHub instance. Currently these repositories mostly live on GitHub.
* [BinderHub](https://binderhub.readthedocs.io/en/latest/) is the computational infrastructure. It is the server technology that turns computational material (e.g. Jupyter notebooks, R scripts, and environment files) into interactive computational environments (a Docker image) and deploys the Binder service in the cloud. It utilizes Kubernetes and JupyterHub in order to simplify the deployment process and make it easy to scale.
* [mybinder.org](https://mybinder.org/) is a single deployment of a BinderHub instance that is public and free to use.

## From Zero to Binder!
A [tutorial](https://the-turing-way.netlify.app/communication/binder/zero-to-binder.html) that walks through how to create a Binder-ready repository on GitHub.