# Project Page Template
This repo creates a template for an academic project page. It has been set up so that no HTML coding is required for a project page. All configuration is done through markdown and yaml files.

## Requirements:
You need to use docker and docker-compose to run this project. If you don't have them installed, follow the instructions [here](https://docs.docker.com/compose/install/).

## Usage:
The files that need to be edited for any project are:
* [_config.yml](./_config.yml)
* [_data/figures.yml](./_data/figures.yml)
* [_data/authors.yml](./_data/authors.yml)
* [project_components/abstract.md](./project_components/abstract.md)
* [project_components/bibtex_ref.md](./project_components/bibtex_ref.md)
* [project_components/description.md](./project_components/description.md)

Everything else should generate automatically
