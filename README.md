# Lookyloo Scraping Tutorial

This tutorial explains why scraping is important (as well as the pitfalls and limitations) and
why Lookyloo is an important tool when investigating a complex website.

-------------------------------

# Target Audience

The target audience for this tutorial is relatively technical, but this tutorial should be
relatively simple to follow by anyone willing to understand how websites work.

-------------------------------

# Setup guide

## Work environment

We assume you have the following environment at your disposal:

* Ubuntu 20.04 or 20.10. It can be an other similar general purpose operating system (Debian 10, Fedora),
  but specialized distros such as Kali Linux are strongly discouraged and won't be supported if you have issues.

  **NOTE**: It is assumed that you're *not* running as root, but the account you're using is administrator (tl;dr: `sudo` works)

* Python 3.8 or 3.9

  **NOTE**: Check it by running `python -V` in a terminal.

* Basic command line tools: `curl`, `wget`, `grep`, `git`
* [Poetry](https://github.com/python-poetry/poetry) 1.1.0 (or more recent), preferably installed this way:
  ```
  curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py > get-poetry.py
  python3 ./get-poetry.py
  ```

  Make sure Poetry is working by running `poetry self -V` in a terminal.

## Install

1. Clone the repository (requires `git`)
  ```bash
  git clone https://github.com/Lookyloo/scraping-tutorial.git
  cd scraping-tutorial
  ```

2. Install the dependencies
  ```bash
  poetry install
  ```

3. Run the lab
  ```bash
  jupyter-lab
  ```

4. Move to your browser. Running `jupyter-lab` should have opened a tab in your favorite browser. If it didn't, look in the terminal for hints.
