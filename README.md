# 🎄 Advent of Code 2020 - Python Solutions 🐍

![Advent of Code Screenshot](./images/aoc_screenshot.png)

This repo contains solutions for [Advent of Code 2020](https://adventofcode.com/2020/) that utilise
tools from the "[open data science stack](https://pydata.org/about/)" such as Python, numpy and
pandas.

## Features

- **`solutions == best_practice`** &nbsp; Solutions aim to use best practices relevant to **data
  scientists** working using the "[open data science stack](https://pydata.org/about/)" such as
  Python, numpy and pandas.
- **`best_practice == working_readable_code`** &nbsp; My definition of "best practice" does not
  mean "only using the Python standard library" or "using minimal code" or even "using the most
  speed efficient code". This is not a [code golf](https://en.wikipedia.org/wiki/Code_golf) repo.
  My goal is to write code that **gets the job done and is easy to understand**. If there's an
  opportunity to showcase a neat feature of Python or one if its third party libraries, even
  better! **_If you think you have a better solution, I'd love to see your PR!_**
- **`code == pep8_compliant`** &nbsp; All `code.py` solution scripts are
  [PEP8](https://www.python.org/dev/peps/pep-0008/) compliant and have furthermore been linted
  using `flake8`, `isort`, `pylint`, auto-formatted using `black`, type hinted using
  [_mypy_](https://mypy.readthedocs.io/) and docstrings are [_Google
  Style_](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html).
- **`pip-sync to start`** &nbsp; The `requirements.txt` is generated and managed by `pip-tools`
  from a minimal requirements set specified in `requirements.in` and has hash-checking for added
  security.
- **The notebooks are written as a teaching resource.** They explain each solutions step-by-step,
  so if there's something you're unfamiliar with in one of the `code.py` scripts, check out the
  notebooks for a guided walkthrough.

## TODO

- Add some tests using `pytest`.
- Integrate `hypothesis` tests, this is a good project for teaching how to use this excellent
  library.

## Setup

```bash
# Get environment
pip install pip-tools
pip-sync

# Add Jupyter kernel
python -m ipykernel install --user --name advent-of-code --display-name "Python (advent-of-code)"

# Install Jupyter extensions JS/CSS & enable required extensions
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter contrib nbextension install --user
```

## Completion status

|        | 1st             | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th | 10th | 11th | 12th | 13th |
| ------ | --------------- | --- | --- | --- | --- | --- | --- | --- | --- | ---- | ---- | ---- | ---- |
| Part 1 | [⭐](./2020/01/) |     |     |     |     |     |     |     |     |      |      |      |      |
| Part 2 | [⭐](./2020/01/) |     |     |     |     |     |     |     |     |      |      |      |      |

|        | 14th | 15th | 16th | 17th | 18th | 19th | 20th | 21st | 22nd | 23rd | 24th | 25th |
| ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| Part 1 |      |      |      |      |      |      |      |      |      |      |      |      |
| Part 2 |      |      |      |      |      |      |      |      |      |      |      |      |

## Back story

After saving Christmas **five years in a row**, you've decided to take a vacation at a nice resort
on a tropical island. Surely, Christmas will go on without you.

The tropical island has its own currency and is entirely cash-only. The gold coins used there have
a little picture of a starfish; the locals just call them **stars**. None of the currency exchanges
seem to have heard of them, but somehow, you'll need to find fifty of these coins by the time you
arrive so you can pay the deposit on your room.

To save your vacation, you need to get all **fifty stars** by December 25th.

Collect stars by solving puzzles. Two puzzles will be made available on each day in the Advent
calendar; the second puzzle is unlocked when you complete the first. Each puzzle grants one star.
Good luck!

## Worth checking out

- Check out [awesome-advent-of-code](https://github.com/Bogdanp/awesome-advent-of-code) for
  solutions in all the languages!
- Reddit's [r/adventofcode](https://www.reddit.com/r/adventofcode/) has solutions for your every
  need. Competitions to find and benchmark the fastest solutions, solutions in
  [ridiculous languages that should never exist](https://www.reddit.com/r/adventofcode/comments/k4e4lm/2020_day_1_solutions/ge8rwqc/?utm_source=reddit&utm_medium=web2x&context=3)
  and even this solution that isn't in a language, but merely the
  [Vim keystrokes required to turn the input into the answer](https://www.reddit.com/r/adventofcode/comments/k4e4lm/2020_day_1_solutions/ge8nctl/).
  There's also poetry and visualisation competitions happening there, because it's #AdventOfCode 2020, why not!
