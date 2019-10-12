# voila-{{ cookiecutter.template_name }}

[![Join the Gitter Chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/QuantStack/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

{{ cookiecutter.package_description }}

## Installation
Add your installation instructions here.

## Example usage

To use the `voila-{{ cookiecutter.template_name }}` template, pass option `--template={{ cookiecutter.template_name }}` to the `voila` command line.


## Development
To view the result of your template locally without having to install this repo as a package you can just run:
```
VOILA_NOTEBOOK=demo.ipynb docker-compose up
```
This will use the template `share/jupyter/voila/templates/{{ cookiecutter.template_name }}` and run the notebook that is stored in notebooks/demo.ipynb.
You can add more example notebooks to the notebooks/ directory.

## License

We use a shared copyright model that enables all contributors to maintain the
copyright on their contributions.

This software is licensed under the BSD-3-Clause license. See the
[LICENSE](LICENSE) file for details.
