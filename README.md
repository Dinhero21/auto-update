# Auto Update

Automatically updating code

## Usage

This program will automatically update when changes to the remote are detected.

The `default` folder includes files that will be only added if missing. Useful for things like default configuration values.

The `overwrite` folder contains files that will be overwritten even if present. Useful for things like dependencies that may change over time.

When `update.sh` is run, it will automatically clone the git repository and update the code accordingly.
