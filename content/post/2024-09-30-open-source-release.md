---
title: "Source code new dynamic site"
date: "2024-09-30"
---

We released the open-source code for the new minimal version of the ParlGov site
— see [post 24/08/2024](/2024/08/24/new-parlgov-site-completed/).

[github.com/hdigital/parlgov-web](https://github.com/hdigital/parlgov-web)

The dynamic website is based on

- an [SQLite](https://www.sqlite.org/) database migrated from
  [parlgov-experimental.db](https://dataverse.harvard.edu/file.xhtml?fileId=10437084&version=1.0)
- a dynamic website with the [Django](https://djangoproject.com) web framework (backend)
  and the [Bootstrap](https://getbootstrap.com/docs/5.3) frontend framework
- an API with [Django REST framework](https://www.django-rest-framework.org/)
- documentation with [MKDocs](https://www.mkdocs.org/)
- testing with [pytest](https://docs.pytest.org/) (about 100% coverage)
- code linting and formatting with [Ruff](https://docs.astral.sh/ruff/)
- CI/CD with [GitHub Actions](https://github.com/features/actions)
- a cloud development environment with [GitHub Codespaces](https://github.com/features/codespaces)
- a reproducible environment with [Docker](https://docs.docker.com/)
- a migration of database tables with [Tidyverse-R](https://tidyverse.org/)

No further additions are planned, but the app will continue to receive security updates (through [Dependabot](https://github.com/dependabot)).

A [working paper](https://doi.org/10.26092/elib/4362) introducing the new version will be published later this year.

---

![Image post](/images/parlgov-codespace.png)
