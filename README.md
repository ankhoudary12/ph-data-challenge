# ph_data_challenge

Repo containing a jupyter notebook answering data challenge questions.

This project requires python > 3.7

In order to setup, run:

`docker-compose up -d`

This starts the Postgres container (docker/docker-compose needs to be installed).

Next, `poetry install` installs the virtual environment and dependencies.

`poetry run jupyter lab` should start the jupyter server and the notebook can be run.

Additionally, I provide a requirements.txt if using venv or another package manager.
