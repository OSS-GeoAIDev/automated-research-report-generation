Project Github: https://github.com/OSS-GeoAIDev/automated-research-report-generation

Command for UV:

uv –version
If uv is not there then install the uv
pip install uv
Once you got the uv
Write this command- uv init <project_name>
Open the project in VS Code

You can also take an alternative approach
First, create a new folder
Open it inside VS Code
Over the VS Code terminal, write this command:  uv init

To create a virtual environment, follow the command below
You can simply write-> uv venv for creating a virtual environment

It will create a virtual env with the default name .venv (this will be the name of the env)

If you want to create with a custom name, follow the command below
uv python list
uv venv <your-env-namne> --python <your-python-version>

Activate the environment
.venv\Scripts\activate.bat

Note: If it is a custom env then copy the path from that folder

uv add -r requirements.txt

uv add ipykernel
