# Oh My Posh Custom Theme

## Description

This repository features a custom theme for [Oh My Posh](https://ohmyposh.dev/), a prompt theme engine for any shell. This theme is designed to provide a visually appealing and informative terminal experience with detailed segments and vibrant colors.

## Features

- **Console Title**: Displays current shell and folder information. If in a Python virtual environment, it shows the Conda environment.
- **Session Segment**: Shows the username and indicates if the session is an SSH session.
- **OS Segment**: Displays the operating system icon.
- **Project Segment**: Shows the project name and version.
- **Shell Segment**: Displays the shell name.
- **Root Segment**: Indicates if the user is root.
- **CMake Segment**: Shows the CMake version.
- **Python Segment**: Displays Python version and virtual environment.
- **Go Segment**: Shows the Go version.
- **Docker Segment**: Displays the Docker context.
- **Rust Segment**: Shows the Rust version.
- **Git Segment**: Displays Git status, including branch, changes, and stash count.
- **Git Version Segment**: Shows the Git version.
- **Bun Segment**: Displays Bun version.
- **Status Segment**: Indicates the last command's exit status.
- **System Info Segment**: Displays system memory usage.
- **Execution Time Segment**: Shows the execution time of the last command.
- **Path Segment**: Displays the current path with folder icons.
- **Time Segment**: Shows the current date and time.

## Installation

1. **Install Oh My Posh**:
   Follow the installation instructions on the [Oh My Posh website](https://ohmyposh.dev/docs/installation).

2. **Clone this repository**:
   ```sh
   git clone https://github.com/riyann00b/oh-my-posh-custom-theme.git
   ```

3. **Copy the theme file**:
   ```sh
   cp oh-my-posh-custom-theme/.mytheme.omp.json ~/.poshthemes/
   ```

4. **Configure your shell**:
   Add the following line to your shell configuration file (e.g., `.bashrc`, `.zshrc`):
   ```sh
   eval "$(oh-my-posh init bash --config ~/.poshthemes/.mytheme.omp.json)"
   ```
   For other shells, replace `bash` with your shell name (e.g., `zsh`).

## Usage

Once installed and configured, open a new terminal session to see the custom theme in action. The prompt will display various segments with information about your session, environment, and system status.

## Customization

To customize the theme, you can edit the `.mytheme.omp.json` file. Refer to the [Oh My Posh documentation](https://ohmyposh.dev/docs/installation) for details on the available configuration options and properties.

## Acknowledgements

- [Oh My Posh](https://ohmyposh.dev/) by Jan De Dobbeleer
- Icons from [Nerd Fonts](https://www.nerdfonts.com/)

---

Enjoy your enhanced terminal experience with the Oh My Posh custom theme!
