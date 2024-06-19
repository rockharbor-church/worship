# Rockharbor Worship

These are the source files that make up [Rockharbor Worship](https://rockharbor-church.github.io/worship/). The site is built using [Material for MKDocs](https://squidfunk.github.io/mkdocs-material/) and [GitHub Pages](https://pages.github.com/).

## Code of Conduct

At Rockharbor, we expect respectful behavior from both administrators and contributors. For more information, see [CODE_OF_CONDUCT.md](https://github.com/rockharbor-church/worship/blob/develop/CODE_OF_CONDUCT.md).

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)

## Building the site locally

To view the docs locally, you'll need Python's `pip` installed. You can check if it's installed by running the following command. If it's not, see the official [Pip Installation Guide](https://pip.pypa.io/en/stable/installation/).

```bash
pip --version
```

Next, open the `worship` directory, then run the following commands:

```bash
pip install mkdocs-material
mkdocs serve
```

Your terminal output will be similar to the following:

```bash
➜  worship git:(main) mkdocs serve                        
INFO    -  Building documentation...
INFO    -  Cleaning site directory
INFO    -  Documentation built in 0.18 seconds
INFO    -  [21:59:33] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO    -  [21:59:33] Serving on http://127.0.0.1:8000/
INFO    -  [21:59:34] Browser connected: http://127.0.0.1:8000/
...
```

Here's what you should see in your web browser:

<img width="1300" alt="Screenshot 2024-06-19 at 8 56 42 AM" src="https://github.com/rockharbor-church/worship/assets/172322910/1fc824ae-7220-4a77-83f0-4d339caa5f2f">
