# Contributing

There are two to contribute to this project.

## Submit a Bug Report or Feature Request

You can submit a bug report, an error in the documentation for a feature request by creating a new issue at repo's [issues](https://github.com/BU-Spark/HerbariaOCR/issues).

If there existing issues, you may want to check if any of those cover your topic, and if so, simply upvote them by giving it a thumbs up.

## Submitting a Proposed Code Change via Pull Request

If you want to submit a change to the code or documentation, follow the instructions
below for setting up your development environment and creating the pull request.

### Clone or Fork this Repo

For project members with write access to the repo, you can directly clone the repo
and push topic branches directly to this repo.

For users that do _not_ have write access to this repo, you will have to fork the repo and create topic branches on your forked repo. After you've pushed or created a new topic branch, you should be given the option to create a Pull Request to the parent repo.

### Setting up Development Environment

Set up a python virtual environment, e.g. 

```sh
pip -m venv .venv
source .venv/bin/activate
```

Install Jupyter.

```sh
pip install jupyterlab
```

Install nbdev.

```sh
pip install nbdev
```

> TODO: instruct how to install with requirements specified in settings.ini.

### Committing new changes

For the most part, all you have to do is add or modify notebooks to `nbs/` folder.

You can see the nbdev [best practices](https://nbdev.fast.ai/tutorials/best_practices.html) for tips on how to generate
documentation from notebooks.

Before you `git commit`, you should execute `nbdev_prepare`, which runs all these [commands](https://nbdev.fast.ai/tutorials/tutorial.html#prepare-your-changes).

After that you can commit all changes.

```sh
git add .
git commit -m "commit message"
git push
```

See [nbdev Getting Started](https://nbdev.fast.ai/getting_started.html) and the Prepare your Changes section of
[tutorial](https://nbdev.fast.ai/tutorials/tutorial.html#preview-your-docs).
