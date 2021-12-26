# {{cookiecutter.project_name}}

Author: {{cookiecutter.author}}
Created: {% now 'utc', '%Y' %}

{{cookiecutter.short_description}}

## Dependencies
* Python 3
* [Go Task](https://taskfile.dev/#/) for automation

## Usage
```bash
# Install dependencies if necessary and launch jupyter notebook
task
# or...
task notebook

# To see all commands
task --list
```
