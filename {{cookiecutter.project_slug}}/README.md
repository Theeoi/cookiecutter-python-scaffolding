# {{ cookiecutter.project_name }}

![Run Pytest](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/test.yml/badge.svg?label=Tests)

{{ cookiecutter.project_description }}

## General Information

*Longer description*

### Technologies

- Python =3.12
- *List of prominent packages*

### Features

- *List of features*
- More features coming! See [Roadmap](#roadmap)..

### Project Layout

    .github/
    
    docs/

    scripts/

    src/

        {{cookiecutter.project_slug}}/
        README.md

    tests/

        functional/
        unit/
        conftest.py

    .gitignore
    pyproject.toml
    README.md

## Setup

### Usage

To use the package do the following:

1. Clone the repo and open it as the working directory.
2. Run `python -m pip install .` to install the package.
3. Run `{{ cookiecutter.project_slug }}` to execute the main package script.

### Contributing

To develop this package you should do the following:

1. Follow the steps outlined in [Usage](#usage) to get the package running.
2. Create a Python virtual environment using your prefered method and activate it.
3. Run `python -m pip install .[dev]` to install the development dependancies.
4. Run `python -m pip install .[docs]` to install the documentation dependancies.
5. *Continue the list accoring to your needs*

## Project Status

*Describe the current status of the project*

### Roadmap

TODO:

- [ ] *List upcoming features and milestones here*

Room for Improvement:

- *List non-crucial possible improvments here*

## Contact

This code was written by [{{ cookiecutter.author_name }}](mailto:{{ cookiecutter.author_email }}).