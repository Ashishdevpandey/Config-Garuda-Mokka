# WhiteSur KDE Configuration

A personal configuration setup for KDE Plasma, designed to replicate the elegant and modern look of macOS Big Sur on Linux. This repository contains configuration files for the WhiteSur global theme, Kvantum theme, and associated wallpapers.

## Features

*   **Global Theme**: WhiteSur (Dark/Light) - A clean and polished theme inspired by macOS Big Sur.
*   **Kvantum Theme**: WhiteSur - Provides consistent styling for Qt applications.
*   **Icons**: WhiteSur icon theme - Matches the overall aesthetic.
*   **Wallpapers**: A collection of high-quality wallpapers to complement the theme.
*   **Fonts**:
    *   **UI Font**: Inter (10pt)
    *   **Monospace Font**: Liberation Mono (10pt)

## Installation

> [!WARNING]
> **Backup your existing configurations before proceeding.** This process involves overwriting configuration files which may result in the loss of your current settings.

### Prerequisites

Ensure you have the following installed on your system:
*   **KDE Plasma Desktop**
*   **Kvantum Manager**: For applying the Kvantum theme.
*   **WhiteSur Gtk/KDE Theme**: It is recommended to install the upstream WhiteSur theme packages for full asset availability.

### Manual Installation

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone https://github.com/Ashishdevpandey/Config-Garuda-Mokka.git
    cd config
    ```

2.  **Copy Configuration Files**:
    Copy the contents of this repository to your local configuration directories.

    *   **KDE Globals & Applet Configs**:
        ```bash
        cp kdeglobals ~/.config/
        cp plasma-org.kde.plasma.desktop-appletsrc ~/.config/
        ```

    *   **Kvantum Theme**:
        ```bash
        mkdir -p ~/.config/Kvantum
        cp -r Kvantum/* ~/.config/Kvantum/
        ```

    *   **Wallpapers**:
        ```bash
        mkdir -p ~/.local/share/wallpapers
        cp -r wallpapers/* ~/.local/share/wallpapers/
        ```

    *   **Color Schemes**:
        ```bash
        mkdir -p ~/.local/share/color-schemes
        cp -r color-schemes/* ~/.local/share/color-schemes/
        ```

3.  **Apply Settings**:
    *   Open **System Settings**.
    *   Go to **Appearance** -> **Global Theme** and select **WhiteSur**.
    *   Go to **Appearance** -> **Application Style** -> **Kvantum** to ensure Kvantum is selected.
    *   Open **Kvantum Manager** and select the **WhiteSur** theme

## License

This configuration is for personal use. The WhiteSur theme and assets are subject to their respective licenses.
