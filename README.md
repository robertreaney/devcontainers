# Multiple Devcontainers

# Setup

1) Install Remote Dev Extension
Name: Remote Development
Id: ms-vscode-remote.vscode-remote-extensionpack
Description: An extension pack that lets you open any folder in a container, on a remote machine, or in WSL and take advantage of VS Code's full feature set.
Version: 0.25.0
Publisher: Microsoft
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

2) Install Docker Desktop

# Use
This repo was structured to switch between different dev environments.

- Open folder in container with `Ctrl+Shift+p` and using command `Dev Containers: Reopen in Container`
- Leave container with `Ctrl+Shift+p` and using command `Dev Containers: Reopen Folder Locally`

One you are in a container, you can use the python debugger in VSCode as normal.