A one-liner phrase describing this project or app

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/247a9fbe41bb49c5805c1ed945910ddd)](https://www.codacy.com/gh/BuildForSDG/python-starter?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=BuildForSDG/python-starter&amp;utm_campaign=Badge_Grade)


## About

What is this project about. Ok to enrich here or the section above it with an image. 

Once this repo has been setup on Codacy by the TTL, replace the above badge with the actual one from the Codacy dashboard, and add the code coverage badge as well. This is mandatory

This is a simple python starter repo template for setting up your project. The setup contains:

- install: poetry via pip. poetry is a dependecy manager.

- poetry: configuration in pyproject.toml

- flake8: for linting and formatting

## Why

Talk about what problem this solves, what SDG(s) and SGD targets it addresses and why these are important

## Usage
How would someone use what you have built, include URLs to the deployed app, service e.t.c when you have it setup


## Setup
You should have Python 3.5+ installed. 

Clone this repo and change into the directory

``bash
git clone https://github.com/BuildForSDG/python-starter.git
``

Change into repo directory

``bash
cd python-starter
``

Install poetry, a dependecy manager for python.

On windows, you will need powershell to install it:

``
(Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py -UseBasicParsing).Content | python
``

After that you will need to restart the shell to make it operational.



On linux and other posix systems (mac included):

``
``

``bash
python3 -m venv .venv/ to create a virtual environment
source .venv/bin/activate
``
Activate and use this environment when implementing your project. Remember to always activate this environment whenever you are working on the project.

Run:

``bash
pip install poetry
poetry install
``

`main.py` is the entry to the project and source code should go into the `src` folder.

All tests should be written in the `test` folder.

#### Hints

- Test: `pytest`
- Install dependencies: 
  `poetry add <dependency>`
  `poetry add --dev <dev-dependency>` for dev dependencies
- Lint: `composer run php-cs-fixer`

## Authors

List the team behind this project. Their names linked to their Github, LinkedIn, or Twitter accounts should siffice. Ok to signify the role they play in the project, including the TTL and mentor

## Contributing
If this project sounds interesting to you and you'd like to contribute, thank you!
First, you can send a mail to buildforsdg@andela.com to indicate your interest, why you'd like to support and what forms of support you can bring to the table, but here are areas we think we'd need the most help in this project :
1.  area one (e.g this app is about human trafficking and you need feedback on your roadmap and feature list from the private sector / NGOs)
2.  area two (e.g you want people to opt-in and try using your staging app at staging.project-name.com and report any bugs via a form)
3.  area three (e.g here is the zoom link to our end-of sprint webinar, join and provide feedback as a stakeholder if you can)

## Acknowledgements

Did you use someone else’s code?
Do you want to thank someone explicitly?
Did someone’s blog post spark off a wonderful idea or give you a solution to nagging problem?

It's powerful to always give credit.

## LICENSE
MIT