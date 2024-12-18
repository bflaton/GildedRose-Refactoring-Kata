# Gilded Rose starting position in Python

For exercise instructions see [top level README](../README.md)

It is strongly suggested to use this archive's devcontainer environment to work in this python playground! Check the prerequisites before clicking below button!

[![Open in Dev Container](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/philips-internal/amp-kata-starter)

## Prerequisites

Best used with [Docker](https://www.docker.com/products/docker-desktop/) and [VS Code](https://code.visualstudio.com/) with the [`Remote Containers`](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) plug-in installed.

## Run the unit tests from the Command-Line

```
python test_gilded_rose.py
```

## Run the TextTest fixture from the Command-Line

For e.g. 10 days:

```
python texttest_fixture.py 10
```

You should make sure the command shown above works when you execute it in a terminal before trying to use TextTest (see below).


## Run the TextTest approval test that comes with this project

There are instructions in the [TextTest Readme](../texttests/README.md) for setting up TextTest. You will need to specify the Python executable and interpreter in [config.gr](../texttests/config.gr). Uncomment these lines:

    executable:${TEXTTEST_HOME}/python/texttest_fixture.py
    interpreter:python
