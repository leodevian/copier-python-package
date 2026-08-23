# copier-python-package

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-purple.json)](https://github.com/copier-org/copier)

A [Copier](https://github.com/copier-org/copier) template for Python packages.

> [!NOTE]
> This Copier template requires:
>
> - [Git](https://git-scm.com/) version 2.
> - [Python](https://www.python.org/) version 3.10 or more.
> - [Copier](https://github.com/copier-org/copier) version 9.6 or more.
> - [Copier Template-Extensions](https://github.com/copier-org/copier-template-extensions) version 0.3.2 or more.

You can use [uv](https://github.com/astral-sh/uv) to install Copier and Copier Template-Extensions:

```bash
uv tool install --with copier-template-extensions copier
```

## Usage

Run `copier copy` to generate your Python package:

```bash
copier copy --trust gh:leodevian/copier-python-package /tmp/python-package
copier copy --trust git@github.com:leodevian/copier-python-package /tmp/python-package
```
