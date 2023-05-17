# 5-local_variables

This script lists all local variables, environment variables, and functions in the current shell environment.

## Description

The `5-local_variables` script is designed to provide information about the local variables, environment variables, and functions that are available in the current shell session.

When executed, the script performs the following actions:

1. Prints all local variables defined within the script's scope using the `declare -p` command.
2. Prints all environment variables using the `env` command.
3. Prints all defined functions using the `declare -F` command.

## Usage

To execute the script, use the following command:

```bash
. ./5-local_variables
