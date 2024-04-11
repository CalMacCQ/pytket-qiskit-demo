# pytket-qiskit-demo

Notebook and slides for qiskit demo day presentation.

## Useful links


[![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://tketusers.slack.com/join/shared_invite/zt-18qmsamj9-UqQFVdkRzxnXCcKtcarLRA#)
[![Stack Exchange](https://img.shields.io/badge/StackExchange-%23ffffff.svg?style=for-the-badge&logo=StackExchange)](https://quantumcomputing.stackexchange.com/tags/pytket)

* [pytket API docs](https://tket.quantinuum.com/api-docs)
* [pytket-qiskit API docs](https://tket.quantinuum.com/pytket-qiskit)
* [User manual](https://tket.quantinuum.com/user-manual) 
* [Example notebooks](https://tket.quantinuum.com/examples)

## Set up environment to run the notebook

The dependencies to run the notebook are specified in `pyproject.toml`.

The main packages required are
* pytket
* pytket-qiskit
* pytket-quantinuum

If you have poetry set up on your machine simply clone the repository and install the dependencies locally. The three packages listed above are also easily installed with `pip`.

```shell
poetry install
```

Next, activate the virtual environment

```
poetry shell
```

Finally, boot up the jupyter server

```shell
jupyter lab
```