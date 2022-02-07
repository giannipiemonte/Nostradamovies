# Nostradamovies

From an 80 000 row dataset containing movie posters, movie synopsis and full IMDB webiste information, you are asked to make movie genre predictions, based on posters only



## Table of Contents

- [Overview](#overview)
- [Resources](#resources)
- [Setup](#setup)
- [Usage](#usage)
- [Support These Projects](#support-these-projects)

## Overview


## Resources

## Setup

# Windows Support

Summary: On Windows, use `py` instead of `python3` for many of the examples in this documentation.

This package fully supports Windows, along with Linux and macOS, but Python is
typically [installed differently on Windows](https://docs.python.org/3/using/windows.html). Windows
users typically access Python through the [py](https://www.python.org/dev/peps/pep-0397/) launcher
rather than a `python3` link in their `PATH`. Within a virtual environment, all platforms operate
the same and use a `python` link to access the Python version used in that virtual environment.


## Virtual Environments

It is best practice during development to create an
isolated [Python virtual environment](https://docs.python.org/3/library/venv.html) using the `venv`
standard library module. This will keep dependant Python packages from interfering with other
Python projects on your system.

On *Nix:

```bash
# On Python 3.9+, add --upgrade-deps
$ python3 -m venv venv
$ source venv/bin/activate
```

On Windows Powershell / `cmd`:

```bash
> py -m venv venv
> venv\Scripts\activate
```

Once activated, it is a good practice to update core packaging tools (`pip`, `setuptools`,
and `wheel`) to the latest versions.

```bash
(venv) $ python -m pip install --upgrade pip setuptools wheel
```


**Setup - Requirements Install:**

For this particular project, you only need to install the dependencies, to use the project. The dependencies
are listed in the `requirements.txt` file and can be installed by running the following command:

```console
pip install -r requirements.txt
```

After running that command, the dependencies should be installed.

