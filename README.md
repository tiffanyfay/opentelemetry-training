# Getting Started with OpenTelemetry
This repository offers a getting started guide for OpenTelemetry, the framework for vendor-neutral telemetry data collection.

## Link to exercises

You can find the exercises/tutorial here: https://novatecconsulting.github.io/opentelemetry-training/

## How to use this repo
This repository consists of two main parts - the tutorial and the hands-on exercises. In the tutorial everything you need to know on how to use OpenTelemetry for the exercises will get explained. The exercises give a hands-on experience on how to use OpenTelemetry in your applications.

The repository utilizes VS Code [Dev Containers](https://code.visualstudio.com/docs/devcontainers/containers) to provide a consistent developer experience across platforms - local and remote.

### Running the lab locally

This will be the default for running this lab. All exercises are described according to this way of using the lab.

To run the lab on your local machine, you'll need to have [Docker](https://docs.docker.com/engine/install/), [VS Code](https://code.visualstudio.com/download), and the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed.
When you open this repository with a locally installed VS Code instance, you'll see a prompt in the bottom right corner.
![Prompt to open the repo inside a Dev container](tutorial/content/exercises/introduction/images/prompt.png)

Press `Reopen in Container` to allow VS Code to use the [devcontainer.json](.devcontainer.json) specification to set up the IDE. If you missed the prompt hit <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (on Mac <kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>) and type `Dev Containers: Rebuild and Reopen in Container`.

* Open this repository in [GitHub Codespaces](https://codespaces.new/NovatecConsulting/opentelemetry-training) or in [Gitpod](https://gitpod.io/#https://github.com/NovatecConsulting/opentelemetry-training)
* Or install [Docker](https://docs.docker.com/engine/install/), [VS Code](https://code.visualstudio.com/download) and the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

With [GitHub Codespaces](https://codespaces.new/NovatecConsulting/opentelemetry-training) a VS Instance in your browser will be opened automatically

The Dev Container spec will automatically open the exercises part with a fully fledged and configured IDE and expose the tutorial on a port to your local system.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/NovatecConsulting/opentelemetry-training) [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/NovatecConsulting/opentelemetry-training)


## How to navigate around the IDE
GitHub Codespaces and Gitpod will automatically run the [devcontainer.json](.devcontainer.json) and are immediately ready to go.
When using this repo with a locally installed VS Code instance you will be greeted by a prompt in the bottom right corner.
![Prompt to open the repo inside a Dev container](assets/prompt.png)

After that the [devcontainer spec](.devcontainer.json) will pull all needed dependencies to build and run the devcontainer in which we will work on the lab content. This can take a bit, so be patient.

If the terminal is not visible open it under `View/Terminal`
![Open the terminal](assets/open-terminal.png)

When you run an application that exposes a port, VS Code will notify you that it is accessible. To open the application just click `Open in Browser` or open your Browser manually and type the URL yourself.
![Open the browser](assets/open-port.png)

When you missed the prompt you can see the open ports in the `PORTS` tab.
![Where to find the forwarded ports](assets/ports.png)

You can at all times use the terminal to run applications and docker images. But you can also use the tab `Terminal/Run Task`
![Tasks](assets/tasks.png)
which will open a terminal and run the needed command automatically. For some exercises you need to run two tasks, which will be explained in the respective lab.
