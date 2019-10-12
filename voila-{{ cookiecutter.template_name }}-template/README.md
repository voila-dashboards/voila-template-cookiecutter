# voila-{{ cookiecutter.template_name }}

[![Join the Gitter Chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/QuantStack/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

{{ cookiecutter.package_description }}

## Installation
Add your installation instructions here.

## Example usage

To use the `voila-{{ cookiecutter.template_name }}` template, pass option `--template={{ cookiecutter.template_name }}` to the `voila` command line.


## Development/contributing
The actual template files can be found in `share/jupyter/voila/templates/{{ cookiecutter.template_name }}/nbconvert_templates/`.

To view the result of the template locally without having to install this repo as a Python package you can just run:
```
make serve
```
This will start Voila in the `example-notebooks/` directory.
Voila will be default be served on http://localhost:8866.
You can change the port mapping in `docker/docker-compose.yml': If you want to have it run on http://localhost:8877, change it to '8877:8866`.

Auto-reload is enabled by default, so all your changes are immediately (well, wait untill it re-rendered...) visible in Voila.

Development of multiple templates within this repo is currently not fully supported, but that may change in the future...

## License

We use a shared copyright model that enables all contributors to maintain the
copyright on their contributions.

This software is licensed under the BSD-3-Clause license. See the
[LICENSE](LICENSE) file for details.
