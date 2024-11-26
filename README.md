# OSNET

![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)
![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)
![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)

OSNET is an Ansible repository used for deploying network configurations for Openstack clusters running BGP.

## Development

```bash
# Setup virtual environment
pyenv virtualenv 3.10.14 osnet
pyenv local osnet
pyenv activate

# You may need to close and re-open your shell before running the following
# Install git hooks, pre-commits should have been installed with poetry above
pre-commit install
```
