# poetry

> Manage Python packages and dependencies.
> More information: <https://python-poetry.org/docs/cli/>.

- Create a new Poetry project in the directory with a specific name:

`poetry new {{project_name}}`

- Install a dependency and its subdependencies:

`poetry add {{dependency}}`

- Install a development dependency and its subdependencies:

`poetry add --group dev {{dependency}}`

- Interactively initialize the current directory as a new Poetry project:

`poetry init`

- Get the latest version of all dependencies and update `poetry.lock`:

`poetry update`

- Execute a command inside the project's virtual environment:

`poetry run {{command}}`

- Bump the minor version of the project in `pyproject.toml`:

`poetry version minor`

- List all poetry subcommands:

`poetry list`
