# EverSDK-DevContainer
EverSDK in a Dev Container

Want to develop EverSDK but don't want to deal with dependencies? Love compartmentalization and want to use VSCode? You may be on the right place

This repo contains the settings for an Ubuntu-based Dev Container that sets up all the dependencies for you. You'll still have to build the EverSDK yourself, but the rest is made easier for you


## Requirements
- Docker
- VSCode

## How do I do this?
1. Create a git repository
2. Download this repo as a zip file - don't clone it - and place its contents (including hidden files) within your newly created repo
3. Add EverSDK as a submodule: `git submodule add --name EverSDK.git -- https://github.com/JohnnyonFlame/EverSDK.git`
4. Open VSCode. If you haven't already, install the Dev Containers extension (ms-vscode-remote.remote-containers)
5. Go to `File` -> `Open Folder` and open your repo
6. When prompted, press "Open in Container" in the notification
7. Be patient while everything is setup
8. Once the setup is done, you're good to go!

All that's left is to follow the instructions in the [EverSDK repo](https://github.com/JohnnyonFlame/EverSDK). At the time of writing, this means:
    - `cd EverSDK`
    - `./build-sdk.sh`

A sample project setup with CMake is included as an optional starting point. If you wish to use it be sure to change "MyProject" to something else in the folder and in the "project" line of the `CMakeLists.txt`.

The project is now ready to be pushed to your own VCS!

Have fun!
