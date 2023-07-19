# Paper Page Template
This repo creates a template for an academic paper page. It has been set up so that no HTML coding is required for a paper page. All configuration is done through markdown and yaml files.

demo;  https://mpslab-asu.github.io/Paper_Page_Template/

## Requirements:
You need to use docker and docker-compose to run this project. If you don't have them installed, follow the instructions [here](https://docs.docker.com/compose/install/).

## Usage:
The files that need to be edited for any paper are:
* [_config.yml](./_config.yml)
* [_data/figures.yml](./_data/figures.yml)
* [_data/authors.yml](./_data/authors.yml)
* [paper_components/abstract.md](./paper_components/abstract.md)
* [paper_components/bibtex_ref.md](./paper_components/bibtex_ref.md)
* [paper_components/description.md](./paper_components/description.md)

Everything else should generate automatically.

### General Instructions:
* Any fields that you do not want to use must be commented out in the yaml files. This is done by adding a '#' at the beginning of the line. (Ex: ln 12 in [_config.yml](./_config.yml) which comments out the supplementary_pdf)


### _config.yml:
The [_config.yaml](./_config.yml) file contains all the information about the paper. The only fields that need to be edited are:

#### 1. Paper Information ->

* **paper_name** : The title of the paper
* **organization** : The organization that the paper is associated with
* **sub_organization** : The department that the paper is associated with

#### 2. Paper Resources ->
* **paper_pdf** : The path to the pdf of the paper
* **supplementary_pdf** : The path to the supplementary pdf of the paper
* **code** : The path to the code for the paper (preferable GitHub)
* **arXiv** : The path to the arXiv page for the paper
* **IEEE** : The path to the IEEE page for the paper
* **favicon** : The path to the favicon for the paper page

### _config.yml: