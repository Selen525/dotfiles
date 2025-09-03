# 🖥️ dotfiles - Simple Setup for Archlinux & Hyprland

[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-latest-blue.svg)](https://github.com/Selen525/dotfiles/releases)

## 🚀 Getting Started

Welcome! This guide will help you easily download and run the dotfiles application for Archlinux and Hyprland. Follow the steps below to get started.

## 📦 System Requirements

Before you download, ensure your system meets these requirements:

- Operating System: Archlinux
- A terminal emulator (e.g., Konsole, Terminal)
- Basic knowledge of the terminal for installation

## 📥 Download & Install

To get the latest version, visit this page to download: [Releases Page](https://github.com/Selen525/dotfiles/releases).

1. Click the link above to access the Releases page.
2. Look for the latest version. It will have the highest version number.
3. Download the `dotfiles.zip` or another available archive file.
4. Once the download completes, unzip the file to a location of your choice.

## ⚙️ Configuration

To set up your dotfiles, follow these steps:

1. Open your terminal.
2. Navigate to the folder where you unzipped the dotfiles:
   ```bash
   cd path/to/unzipped/folder
   ```
3. Copy the dotfiles to your home directory:
   ```bash
   cp -R ./* ~/
   ```

This step will overwrite any existing dotfiles in your home directory. Backup your current dotfiles if needed.

## 🛠️ Features

This dotfiles repository includes configurations for:

- **Hyprland:** A modern and customizable window manager.
- **Neovim:** An enhanced version of Vim for text editing.
- **Tmux:** A terminal multiplexer that allows multiple terminal sessions.

Each application has its own configuration files that you can customize further as per your needs.

## 🔍 Customization

After you copy the dotfiles, you might want to customize them:

- **Neovim Configuration:** Located in `~/.config/nvim/init.vim`. Edit this file to change editor settings.
- **Tmux Configuration:** Found in `~/.tmux.conf`. Adjust this file to set your preferred terminal parameters.
- **Hyprland Settings:** Located in `~/.config/hypr/hyprland.conf`. Modify this according to your workflow.

## 💡 Troubleshooting

If you encounter issues during installation, consider the following tips:

- Ensure you have installed required applications on your system.
- Check file permissions. Ensure the copied files are accessible.
- View the terminal output for any error messages. These can guide you to the specific problem.

## 🌐 Community & Support

For assistance and community support, you can:

- Visit the [GitHub Issues Page](https://github.com/Selen525/dotfiles/issues) for any questions or to report bugs.
- Look for discussions related to Archlinux and Hyprland in forums or chat groups for user-contributed tips.

## 🔗 Additional Resources

- **Archlinux Wiki:** [Archlinux Documentation](https://wiki.archlinux.org)
- **Hyprland Guide:** Check Hyprland’s official documentation for advanced setups.
- **Neovim Tutorials:** Numerous online resources are available to learn about Neovim's features and usage.

## 📞 Contact

For direct questions regarding this repository, feel free to create an issue on the repository page. Your feedback is important, and we appreciate your contribution to the community.

## ⚠️ License

This project is licensed under the MIT License. This means you can modify and distribute it as you like, provided that you include a copy of the original license.