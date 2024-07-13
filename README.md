# Oh My Posh Custom Theme
A feature-rich and visually appealing Oh My Posh theme designed for developers.

![Theme Screenshot](https://github.com/riyann00b/Oh-My-Posh-Theme/blob/main/Screenshot%20from%202024-07-14%2005-00-11.png)

## Description

This repository features a custom theme for [Oh My Posh](https://ohmyposh.dev/), a prompt theme engine for any shell. This theme is designed to provide a visually appealing and informative terminal experience with detailed segments and vibrant colors.

## Features

This theme provides a comprehensive set of segments for various development environments and tools:

- **User and System Info**: Displays username, OS, and shell information
- **Development Environments**: 
  - Node.js (with npm, yarn, and pnpm support)
  - Python (with virtual environment detection)
  - Java
  - Kotlin
  - Go
  - Rust
  - Ruby
  - PHP
  - .NET
  - Swift
  - Scala
  - Clojure
  - Elixir
  - Erlang
  - Lua
  - Flutter
- **Cloud Platforms**:
  - AWS
  - Azure
  - Google Cloud Platform (GCP)
- **DevOps Tools**:
  - Docker
  - Kubernetes
  - Helm
  - Terraform
- **Version Control**:
  - Git (with detailed status information)
  - Git version
- **Package Managers**:
  - npm
  - Bun
- **Frameworks**:
  - React
- **Cloud Services**:
  - Firebase
- **Media Players**:
  - Spotify
  - YouTube Music


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
