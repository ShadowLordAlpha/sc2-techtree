# StarCraft II tech tree and dependencies

All SC2 structures, units, abilities, researches and dependencies between these, in machine readable JSON format.

This repository contains Python scripts for data generation.

# Development

- Install python3.7 or newer
- `pip install poetry --user`

The Python code to generate new data is under `generate`.

You can just run `poetry run python run.py` to generate new `/data/data.json`.

# Missing data? Invalid data? Other issues?

Please [open a new issue in GitHub](https://github.com/BurnySc2/sc2-techtree/issues/new).

Pull requests to fix things or for extensions are welcome as well,
although I suggest asking me first by opening an issue or otherwise.
The data model changes are usually quite hard to get right, and the
data collection script itself is quite complicated and full of edge
cases.
