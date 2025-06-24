# preCICE Config-Visualizer GUI

The `config-visualizer` is a tool meant to help visualize and debug precice configuration xml files. This tool produces a dot file as output, which visualizes the various participants, communicators and meshes defined in the configuration file and the movement of data between them.
This GUI offers an interactive way to quickly inspect, explore and study preCICE configuration files.

## Installation options

Install directly from PyPi using [pipx](https://pipx.pypa.io/stable/) or via pip:

```
pipx install precice-config-visualizer-gui
```

## Usage

```
precice-config-visualizer-gui [CONFIG-FILE]
```

You can launch the GUI directly from the command line.
Passing the path to a configuration file is optional.
All further adjustments are made directly in the GUI.

## System integration

Until existing tools provide an automatic way to integrate applications into the system, this has to be done manually.

For pipx users, run the following command [which downloads this file](https://gist.githubusercontent.com/fsimonis/a08c3771abf808b0534d658bcb563f90/raw/10717f5b2afbf2d3c05ecb9f5c7eeaae4bbe868a/org.precice.configvisualizer.desktop)

```console
mkdir -p ~/.local/share/applications && wget -O ~/.local/share/applications/org.precice.configvisualizer.desktop https://gist.githubusercontent.com/fsimonis/a08c3771abf808b0534d658bcb563f90/raw/10717f5b2afbf2d3c05ecb9f5c7eeaae4bbe868a/org.precice.configvisualizer.desktop
```

You may have to logout and login for your desktop environment to detect the file.
Now you can open XML files directly with the config-visualizer and see the application in your launcher.

## Licensing

The license was changed from GPLv3 to MIT in approval of the copyright holder Frédéric Simonis (@fsimonis frederic.simonis@ipvs.uni-stuttgart.de) decided on 24. June 2025 12:40 CET.

