# Hackathon Ponts ENPC

## Install

- when opening VSCode, install the suggested extensions (Python, Black Formatter and Pylance)
- create your python environment `python3 -m venv .venv`
- copy the `.env.example` file to a `.env` file
- replace the `OPENAI_API_KEY` env variables with the real values
- activate your environment with `source .venv/bin/activate`
- install the requirements with `pip install -r requirements.txt`
- download necessary data with `python -m nltk.downloader all`
- run the server with `flask --app main run --debug`

The server should answer on http://localhost:5000

You can deactivate the environment with `deactivate`.

## Adding librairies

if you need to use a new librairies, you can do it with pip
`pip install [library name]` or `pip3 install [library name]`

##modifs:   
dans le terminal bash: py -m venv .venv
dans bash: source .venv/Scripts/activate
dans le powershell: pip install openai==0.28 
dans le powershell: flask run

