# breast_cancer_diagnosis

[![pipeline status](https://gitlab.lasse.ufpa.br/2020-ai-testbed/ai-testbed/simple-ml-ran-slicing/badges/master/pipeline.svg)](https://gitlab.lasse.ufpa.br/2020-ai-testbed/ai-testbed/simple-ml-ran-slicing/-/commits/master)

Python implementation to the paper "Evaluation of computationally intelligent techniques for breast cancer diagnosis" published on Neural Computing and Aplications journal (2021).

## Install

- Install [pipenv](https://github.com/pypa/pipenv)
- Install dependencies using pipenv: `pipenv install --skip-lock`  (it is important to always use the flag `--skip-lock` because pipenv has a problem which can take a lot of time to install if not used)
- To access the virtual environment created, run `pipenv shell`, now all commands which you run will be performed into virtual enviroment created
- Activate pre-commit hooks to use [black formatter](https://github.com/psf/black), [flake8 lint](https://gitlab.com/pycqa/flake8) and [Isort references](https://github.com/timothycrosley/isort). Run `pre-commit install`. Now every time you make a commit, black formatter, flake8 and isort will make tests to verify if your code is following the [patterns](https://realpython.com/python-pep8/) (you can adapt your IDE or text editor to follow this patterns, e.g. [vs code](https://code.visualstudio.com/docs/python/python-tutorial#_next-steps))

## Dataset

- Instructions to download the dataset

## Training ML models

- Instructions to execute the training of ML models

## Running

- Inside the virtual environment, execute the test server using `python SCRIPT_NAME_HERE`
- 