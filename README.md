# Focused Hawking

![Python v3.8](https://img.shields.io/badge/python-3.8-blue?style=for-the-badge)

## Proposal

> _VS Code Dev Container to the rescue!_

This repository contains a template project for Python 3 applications, also with Docker Machine from host inside the development container.

Works fine in OSX, I assume that works fine too in Linux. About Windows, I have no tested and probably I will not.

## Usage

Using VS Code with Dev Container, select `Open Folder in Container...` option.

## Tips

- Add containers to `.devcontainer/docker-compose.yml` to call applications as _localhost_.
- You don't need to use _virtual env_, this environment already is isolated. But probably you should, is a good practice and someone maybe dislikes use your IDE setup for development.
- You can add dependencies in `.devcontainer/requirements.txt` to have a ready-to-go development environment!

## Acknowledgements

I'm too lazy to name properly a repository, so I use a docker-like [name generator](https://codepen.io/mikedryan/details/vLrgqr). Weird? Yeap. Confused? A lot. But this Github only works as a code backup and I really dislike being blocked because my lack of creativity naming stuff.

The same principle is applied to commits messages, "..." is too common, so why not improve with this wonderful `git alias`?

```
[alias]
	random = !git add -A && git commit -m \"$(curl -s http://whatthecommit.com/index.txt)\"
```

Awesome! Children, don't do this at home. Not at work either!

## License

The MIT License (MIT). To see the details of this license, see the [license file](LICENSE.md).

:octocat:
