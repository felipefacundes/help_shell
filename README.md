# help_shell: Simplified Help Management for Shell Scripts

Imagine creating help functions, and typing whatever you want in the terminal, just create a simple function, instead of creating an entire script, this is the premise of `help_shell`.

The `help_shell` script is an efficient and user-friendly tool designed to dynamically display help information for your Bash functions. As part of the [shell_utils framework](https://github.com/felipefacundes/shell_utils), one of the most comprehensive collections of utilities and scripts, this script simplifies the creation and management of help documentation for your custom functions.

## Key Features

- **Dynamic Help Display**: Automatically lists all available functions with descriptions extracted from comments.
- **Interactive Search**: Search for functions by name or description using a clean and intuitive menu powered by `whiptail`.
- **Flexible Usage**: Allows for specifying functions as command-line arguments or interacting via the dynamic menu.
- **Integration Ready**: Seamlessly integrates with the `shell_utils` framework, leveraging pre-defined variables and resources.

## Prerequisites

- Bash shell (version 4.0 or higher recommended)
- `whiptail` for interactive menus
- A functional installation of the `shell_utils` framework

## Installation

- Clone the `shell_utils` repository:

   ```bash
   git clone https://github.com/felipefacundes/shell_utils ~/.shell_utils
   ```

## Usage

Run the script directly to explore available functions:

```bash
./help_shell
```

### Command-line Arguments

You can pass function names as arguments to call them directly:

```bash
./help_shell function1 function2
```

### Interactive Help

Use the `-h` or `--help` flags to access the help menu:

```bash
./help_shell -h
```

## License

This script is licensed under the GPLv3. See the LICENSE file in the [shell_utils repository](https://github.com/felipefacundes/shell_utils) for details.

## Credits

Developed by Felipe Facundes as part of the shell_utils framework.
