# Braubuddy

*Braubuddy* is a temperature management framework written in Python.

Conceived as a means of monitoring and controlling the fermentation temperature of beer, *Braubuddy* can be used in any situation where visibility and/or control of temperature is critical.

## Conventions

* Setup
    * Pyproject.toml
* Formatting
    * Black
* Testing
    * Tox
    * Pytest
    * Coverage
* Badges
* Builds
    * Travis / CircleCI (TBD)
* Publishing
    * [SemVer](https://semver.org/)
    * [Changelog](https://keepachangelog.com)
    * [PyPI](https://pypi.org/project/braubuddy/)
* Line limit: 100
* Documentation
    * Type annotations
    * Param descriptions in docstrings
    * Sphinx (readthedocs/self-hosted TBD)
* Security
    * [Safety](https://pyup.io/safety/)
    * [Bandit](https://pypi.org/project/bandit/)

## Platform

* Backend
    * Websocket
        * Micropython
    * Framework TBD
        * aiohttp
        * tornado
        * responder
    * Protocol TBD
        * JSON-RPC
        * socketio
* Frontend
    * React Native
