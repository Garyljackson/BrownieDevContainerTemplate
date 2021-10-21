# Base Container

- [Ubuntu](https://github.com/microsoft/vscode-dev-containers/blob/v0.202.5/containers/ubuntu/.devcontainer/base.Dockerfile)

# Components Installed

- Python 3 + pip
- node.js (17.x) + npm
- [py-solc-x](https://pypi.org/project/py-solc-x/)
- [eth-brownie](https://pypi.org/project/eth-brownie/)
- [ganache-cli](https://www.npmjs.com/package/ganache-cli)

# Visual Studio Code Extensions

- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [solidity](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity)

## To Initialise a new project

```
brownie init -f
```