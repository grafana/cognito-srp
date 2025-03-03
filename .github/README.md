
**Fork of the repository https://github.com/alexrudd/cognito-srp for review.**

The original `README.md` is located in the root of the repository. This `README.md` is located in the `.github` directory and is dedicated to reviewers.

## Environment

We use [Development Containers](https://containers.dev/) to provide a reproducible review environment. We recommend that you do the same. In this way, it is guaranteed that the appropriate version of the tools required for review 
will be available.

**Without installing software**

You can *review without installing any software* using [GitHub Codespaces](https://docs.github.com/en/codespaces). Simply [create a codespace for the repo](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository).


**Using an IDE**

You can review conveniently using [Visual Studio Code](https://code.visualstudio.com/) by installing the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension. You *don't need to install any other software* to review. Clone the repository and open the folder with Visual Studio Code. It will automatically detect that the folder contains a Dev Container configuration and ask you whether to open the folder in a container. Choose **"Reopen in Container"**.

**The hard way**

All the tools used for development are free and open-source, so you can install them without using *Development Containers*. The `.devcontainer/devcontainer.json` file contains a list of the tools to be installed and their version numbers.

## Usage

The `.golangci.yml` file contains the golangci-lint configuration.

Running golangci-lint from the root of the repository:

```bash
golangci-lint run
```
