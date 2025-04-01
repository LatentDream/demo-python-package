# My Package

A simple Python package that can be installed directly from Git.

## Installation

```bash
pip install git+https://github.com/yourusername/my_package.git
```

If private:
```basg
pip install git+https://<access_token>@github.com/<repository_url>#<branch_or_tag>
```

More info [here](https://dnmtechs.com/installing-packages-from-private-github-repositories-using-pip-in-python-3/)

## Usage

```python
from my_package import hello

print(hello())  # Outputs: Hello from my_package!
```
