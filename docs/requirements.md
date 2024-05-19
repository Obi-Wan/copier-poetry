# Requirements

To use this Copier template, you will need:

- [git v2](https://git-scm.com/)
- [Python 3](https://www.python.org)
- [Copier](https://copier.readthedocs.io/en/stable/)

To install git version 2,
[follow the official instructions](https://git-scm.com/downloads).

To install Python 3,
download and install it from
[the official website](https://www.python.org/downloads/),
or install it with [pyenv](https://github.com/pyenv/pyenv):

```bash
# install pyenv
git clone https://github.com/pyenv/pyenv ~/.pyenv

# setup pyenv (you should also put these three lines in .bashrc or similar)
export PATH="${HOME}/.pyenv/bin:${PATH}"
export PYENV_ROOT="${HOME}/.pyenv"
eval "$(pyenv init -)"

# install Python 3
pyenv install 3.10

# make it available globally
pyenv global system 3.10

# finally, restart your shell
# to make sure your environment is up-to-date
```

To install Copier, use `pip` or `conda`:

```bash
pip install --user copier
```

```bash
conda install copier -c conda-forge
```
