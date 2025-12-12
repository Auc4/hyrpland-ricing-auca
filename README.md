# ⚙️ Auc4-Dotfiles: High-Performance, Secure Linux Workflow

## Project Overview

This repository holds the configuration files (dotfiles) for my primary computing environment: a custom-built, high-performance workflow based on **Arch Linux**.

The entire system is optimized for speed, security, and a minimalist design, which is essential for resource-intensive tasks such as large-scale data processing and code automation.

### Key Features & Technical Details

This setup demonstrates deep operational knowledge of Linux systems, crucial for Data Science and DevOps roles:

| Feature | Description | Relevance |
| :--- | :--- | :--- |
| **Full Disk Encryption** | Implemented **LUKS** for complete disk encryption. | Ensures **data security** and confidentiality for sensitive models and data. |
| **Window Manager** | Customized configuration for **Hyprland** (a dynamic tiling window manager for Wayland). | Provides a fast, low-latency environment to **maximize productivity** and screen efficiency. |
| **GPU Optimization** | Manual setup and optimization of **NVIDIA Drivers**. | Guarantees peak hardware performance for computing and rendering tasks. |
| **Workflow Tools** | Configuration files for **swaync** (notifications) and custom terminal elements (e.g., Zsh/Vim keybinds). | Creates a distraction-free and highly efficient command-line interface. |

---

## 🖼️ Screenshots & Workflow

*(**Action Required:** Please replace the link below with a link to your images, GIF, or video showing the setup.)*

[View the personalized desktop environment and workflow in action.]

---

## 🚀 Installation & Usage

These files are primarily a personal reference, but they can be used to replicate the environment by creating symlinks (or using a tool like GNU Stow) after a minimal Arch installation.

1.  **Dependencies:** Install all necessary packages (Hyprland, Waybar, SwayNC, etc.).
2.  **Clone:** Clone this repository to your machine.
3.  **Apply Configs:** Create symbolic links from these files to their respective locations in `~/.config/`.
4.  **Security:** Implement LUKS encryption during the initial disk setup phase.

---
###### Configured and Maintained by Sebastián Aucapiña (@Auc4)
###### Last Updated: December 2025
