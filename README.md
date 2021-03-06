# perceval-azuredevops 

Bundle of Perceval backends for Azure Devops.
This bundle is inspired from https://github.com/chaoss/grimoirelab-perceval-weblate. For more information on GrimoireLab project, go check https://chaoss.github.io

## Backends

The backends currently managed by this package support the next repositories:

* Azure DevOps

## Requirements

* Python >= 3.6
* python3-requests >= 2.7
* grimoirelab-toolkit >= 0.1.12
* perceval >= 0.17.1

## Installation

To install this package you will need to clone the repository first:

```
$ git clone https://github.com/chaoss/grimoirelab-perceval-azuredevops.git
```

Then you can execute the following commands:
```
$ pip3 install -r requirements.txt
$ pip3 install -e .
```

In case you are a developer, you should execute the following commands to install Perceval in your working directory (option `-e`) and the packages of requirements_tests.txt.
```
$ pip3 install -r requirements.txt
$ pip3 install -r requirements_test.txt
$ pip3 install -e .
```

## Examples

### Azure Devops

```
$ perceval azureboard $projectURL $PersonnalAccessToken
```

## License

Licensed under GNU General Public License (GPL), version 3 or later.
