---
summary: Welcome 👋
draft: false
authors:
  - astronemir
lastmod: 2020-12-13T00:00:00Z
title: Welcome to my website
subtitle: Welcome 👋  Under construction.
date: 2020-12-13T00:00:00Z
featured: false
tags: []
categories: []
projects: []
image:
  caption: ""
  focal_point: ""
  placement: 2
  preview_only: false
---
```python
import this
```

## [](https://wowchemy.com)My projects:\
\
PROJECTS

### My portfolio projects can be found on my [GitHub](https://github.com/emirkmo). 

Since I enjoy solving problems with programming I have been involved in many projects. I highlight some recent ones here which show my latest skills. The decisions behind the coding and hosting choices can be found in their individual blog posts (upcoming). For now, feel free to explore them on GitHub!

#### FLOWS

#### Astronomy image analysis pipeline

https://github.com/SNFLOWS\
Utilized Python, Linux, Git, GitHub, bash, Cron, SQL, PostGreSQL,\
Docker to create data reduction pipeline that has served over\
100,000 photometric measurements.

#### RawSightML

#### [](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)Raw python/numpy (vectorized), object-oriented, Machine Learning library

https://github.com/emirkmo/rawsight_ML\
Implemented acceptance tests against Tensorflow and Scikit-\
Learn.\
Used SOLID design principles to make easily extensible and\
readable code to provide insight into ML algorithms, with\
interfaces defined by Protocol classes.\
Implemented Linear, Logistic, Softmax, Polynomial regression,\
normalizers, cost functions, regularization, batch gradient descent,\
sequential and convolutional neural nets with dense layers, back\
propagation, decision trees.

#### astroSN

#### [](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)Python pandas based, typed, extensible, supernova time-series analysis and plotting library

Reduced on-boarding time for new students into bachelor\
research projects by two weeks by publishing on PyPi (pip) a\
supernova time-series analysis library, also containing an ETL\
photometry ingest pipeline, using easy to extend abstract classes\
and protocols.

## tnsquery

#### [](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)asychronous REST API for transient data queries developed with FASTAPI, SQLAlchemy, and Docker

https://github.com/emirkmo/tnsquery\
Implemented a local postgreSQL database as a caching/main\
database, external private API as central-authority service, and\
deployed with docker containers using Portainer for container\
management on self-built bare-metal Linux server, served via\
CloudFlare tunnels instead of nginx reverse proxy. Will be\
implemented into large open-source community Astropy package\
to provide limited-authentication API queries not possible via the\
official API, which is locked behind professional astronomer\
credentials page.\
Full python packaging eco-system with poetry, pip, pre-commit\
hooks mypy, black, flake8, Alembic migrations, github actions, dev\
and deployment containers

### Tendrils

#### [](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)Python API wrapper around PHP webserver API  

Developed simple API to give researchers programmatic access to data products of FLOWS pipeline and related external APIs.

#### flows_get_brightest

#### Astronomy observational planner

python script to query catalogs, intelligently place instrument on sky to

avoid bright stars, and produce finder charts.

#### Object-oriented grid-graph algorithm solutions in Python

Object oriented standard grid-graph (island) traversal algorithms,\
implemented with multi-D breadth first and depth first search,\
allowing for non-standard path-traversal logic, in simple to read\
and extend raw python.



# Selected Open Source Contributions

\- **Astropy**: Made Extended CSV (ECSV) v.1.0 backwards compatibile\
with v0.9, added regression tests, allowing many projects to finally\
upgrade to the latest version of Astropy.

 \
  - **SVOFilters**: Added data validation and cleaning to the web API for\
queries resulting in non-monotonically increasing bandpass filter\
profiles, and for N repeated entries using BFS; made errors more\
specific.

 \
  - **Pyscript**: Contributed How-To guide on making async HTTP\
requests using PyScript and pyodide using JavaScript Fetch API,\
using a pure python wrapper, addressing the most commonly\
asked issue and question of the missing requests module.

 

[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)[](<>)  - **Scikit-Learn:** Made Gaussian Mixture Model initialization more\
robust by allowing passing in user-provided callables and\
simplified the model inputs, provided docs, regression tests, and\
increased test coverage of sklearn.mixture module.

 \
  - **Photutils:** Found, reproduced, diagnosed, and fixed bug with\
point-spread-function centroid finding algorithm and added\
regression tests.