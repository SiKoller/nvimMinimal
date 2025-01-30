# Minimal Neovim Configuration with Harpoon, Typr, and Markdown Preview

This repository contains a minimal Neovim configuration with Harpoon, Typr, and Markdown Preview pre-installed and configured. It's designed to provide a clean starting point for your Neovim journey, allowing you to quickly get up and running with these essential plugins.

## Features

*   **Minimal and Fast:**  Focuses on essential configurations for a smooth and responsive editing experience.
*   **Harpoon Integration:**  Quickly jump between frequently edited files.
*   **Typr Integration:**  Enhanced text objects and motions for faster editing.
*   **Markdown Preview:**  Real-time preview of your Markdown files.
*   **Clean Key Mappings:**  Intuitive and efficient keybindings for common tasks.
*   **Easy to Extend:**  Designed to be easily customized and extended with your preferred plugins and configurations.

## Prerequisites

*   Neovim (version 0.5 or later)

## Installation

1.  Clone this repository:

    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://www.google.com/search?q=https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git) ~/.config/nvim
    ```

    Replace `YOUR_USERNAME/YOUR_REPO_NAME` with the actual URL of your repository.

2.  Open Neovim:

    ```bash
    nvim
    ```

    Neovim will automatically install the required plugins using `packer.nvim` (or your package manager if you change it).

## Configuration

The main configuration file is located at `~/.config/nvim/init.lua`.  This file is structured to be easily understood and modified.

### Key Mappings

Here are some of the key mappings:

*   **Harpoon:**
    *   `<leader>a`: Mark the current file with Harpoon.
    *   `<leader>n1` - `<leader>n4`: Jump to the marked files.
    *   `<C-a>`: Show the Harpoon menu.

*   **Markdown Preview:**
    *   `<leader>mp`: Toggle the Markdown preview.

*   **Typr:**
   *  Typr integrates seamlessly with normal Neovim motions.  Refer to the Typr documentation for specific keybindings.  It generally enhances existing motions like `iw`, `aw`, `i"`, `a"` etc.

*   **Other Useful Mappings (Examples - add your own!):**
    *  `<leader>w`: Save the current file.
    *  `<leader>q`: Quit Neovim.

You can customize these key mappings and add your own in the `keymaps.lua` file.

## Extending the Configuration

To add more plugins or customize the configuration further, you can modify the `init.lua` file.  The repository uses `packer.nvim` as a plugin manager.  You can replace it with other managers like `vim-plug` or `lazy.nvim` if you prefer.

## Troubleshooting

If you encounter any issues, please:

1.  Check the Neovim logs: `~/.local/state/nvim/lsp.log` (or similar, depending on your system)
2.  Ensure that all the dependencies are installed correctly.
3.  Consult the documentation for Harpoon, Typr, and Markdown Preview.
4.  Open an issue on this repository.

## Contributing

Contributions are welcome!  Please open an issue or submit a pull request.

## License

[MIT License](LICENSE) (or your preferred license)
