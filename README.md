# McWizard

```
Update V1.1
> fixed ngrok installation
> added ngrok console
```

<img src="https://github.com/Cr0mb/mcWizard/assets/137664526/eb5501c0-c0f3-4260-bfa0-bbc69929dd14" width="300" height="auto" alt="image">

`mcWizard` is a Python script designed to automate the setup and management of a Minecraft server. This script provides an easy-to-use menu interface to perform various server-related tasks, including installation, starting/stopping the server, updating to the latest build, and more. Additionally, it integrates with Ngrok to allow for easy remote access to the Minecraft server.

## Features

- **Automated Setup**: Installs necessary packages and dependencies.
- **Server Management**: Start, stop, and restart the Minecraft server.
- **EULA Management**: Automatically accepts the Minecraft EULA.
- **Ngrok Integration**: Sets up and runs Ngrok to expose the server to the internet.
- **Console Access**: Provides access to the Minecraft server console.
- **Plugin Management**: Downloads plugins directly to the server's plugin folder.

## Prerequisites

- Python 3.x
- `pyfiglet` (will be installed automatically if not found)
- `openjdk-16-jre-headless`
- `curl`
- `tmux`
- `sudo` privileges

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/cr0mb/mcWizard.git
    cd mcWizard
    ```

2. Run the script:
    ```sh
    python mcWizard.py
    ```

## Usage

Run the script and follow the on-screen menu to manage your Minecraft server. The available options include:

1. **Update & Install**: Update the system and install necessary packages.
2. **Download Minecraft Server.jar and Ngrok**: Download the latest stable build of the Minecraft server and Ngrok.
3. **Load EULA**: Accept the Minecraft EULA.
4. **Kill All Java Processes**: Terminate all running Java processes.
5. **Check and Set EULA**: Ensure the EULA is set to true.
6. **Create Start Script**: Create a start script for the Minecraft server.
7. **Create Ngrok Script**: Create a shell script to perform Ngrok commands (requires Ngrok auth token).
8. **Check Server Status**: Check if the Minecraft server and Ngrok are running.
9. **Update Minecraft Server**: Update the Minecraft server to the latest stable build.
10. **Download Plugin to Plugin Folder**: Download a plugin to the server's plugin folder.
11. **Restart the Server**: Restart the Minecraft server and Ngrok.
12. **Send Console Commands**: Send commands directly to the Minecraft server console.

Additionally, you can start, stop the server and Ngrok, or open the console GUI using the respective options.

