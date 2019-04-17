![Logo](https://raw.githubusercontent.com/idealista/kibana_role/master/logo.gif)

[![Build Status](https://travis-ci.org/idealista/kibana_role.png)](https://travis-ci.org/idealista/kibana_role)

# Kibana Ansible role

- [Getting Started](#getting-started)
  - [Prerequisities](#prerequisities)
  - [Installing](#installing)
- [Usage](#usage)
- [Testing](#testing)
- [Built With](#built-with)
- [Versioning](#versioning)
- [Authors](#authors)
- [License](#license)
- [Contributing](#contributing)

## Getting Started

**THIS ROLE IS FOR 6.x**

Ansible role for 6.x Kibana. Currently this works on Debian based linux systems. Tested platforms are:

* Debian 8
* Debian 9

These instructions will get you a copy of the role for your ansible playbook. Once launched, it will install [Kibana](https://www.elastic.co/products/kibana).
### Prerequisities

#### To execute this role:

Ansible 2.7.5.0 version installed.

#### For testing purposes:

* Python 3.6
* [Molecule](https://molecule.readthedocs.io/)
* [Pipenv](https://github.com/pypa/pipenv) 
* [jmespath](http://jmespath.org/) 
* [Docker](https://www.docker.com/) as driver


### Installing

Create or add to your roles dependency file (e.g requirements.yml):

```yml
- src: http://github.com/idealista/kibana_role.git
  scm: git
  version: 1.0.0
  name: kibana
```

or using [Ansible Galaxy](https://galaxy.ansible.com/idealista/kibana_role/) as origin if you prefer:

```
- src: idealista.kibana_role
```

Install the role with ansible-galaxy command:

```
ansible-galaxy install -p roles -r requirements.yml -f
```

Use in a playbook:

```yml
---
- hosts: someserver
  roles:
    - role: kibana
```

## Usage

Look to the [defaults](defaults/main.yml) properties file to see the possible configuration properties.


## Testing

```sh
pipenv install -r test-requirements.txt
pipenv run molecule test
```

Kibana Admin UI should be accessible from docker container host at URL:

http://localhost:5601

## Built With

![Ansible](https://img.shields.io/badge/ansible-2.7.5.0-green.svg)

## Versioning

For the versions available, see the [tags on this repository](https://github.com/idealista/kibana_role/tags).

Additionaly you can see what change in each version in the [CHANGELOG.md](CHANGELOG.md) file.

## Authors

- **Idealista** - *Work with* - [idealista](https://github.com/idealista)

See also the list of [contributors](https://github.com/idealista/kibana_role/contributors) who participated in this project.

## License

![Apache 2.0 License](https://img.shields.io/hexpm/l/plug.svg)

This project is licensed under the [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) license - see the [LICENSE](LICENSE) file for details.

## Contributing

Please read [CONTRIBUTING.md](.github/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
