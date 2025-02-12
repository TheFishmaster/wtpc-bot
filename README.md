# WTPC Bot

The Wake Tech Programming Club Discord bot.

-   [Discord.py Documentation](https://discordpy.readthedocs.io/en/stable/)

## Local Setup

Python 3.11 or newer is required. You can download it [here](https://www.python.org/downloads/). Verify that it installed by running `python --version` (you might have to use the `python3` or `python3.11` command instead if you have another version installed).

[VSCode](https://code.visualstudio.com/) is also recommended as a code editor. Make sure to have the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) installed. See [VSCode Setup](#vscode-setup) for more information.

1. Clone the repository to your local machine.
2. `cd` into the project directory.
3. `python -m venv env` to create a virtual environment.
4. `pip install -r requirements.txt` to install the necessary dependencies.
5. Make sure to rename `.env.example` to `.env` and replace the placeholder value of `API_KEY` with your actual API key.
6. Start the bot with `python -m bot`.

## VSCode Setup

If you're using VSCode, make sure the Python interpreter is configured correctly. Enter the Command Palette using Ctrl+Shift+P (or CMD+Shift+P on macOS) and select `Python: Select Interpreter` and then select `Python 3.11.x ('env': venv) ./env/bin/python`.

Also make sure to have the [Mypy](https://marketplace.visualstudio.com/items?itemName=matangover.mypy) extension installed for type checking support.

## License

[MIT](./LCIENSE)
