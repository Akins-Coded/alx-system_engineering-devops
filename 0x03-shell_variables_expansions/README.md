# Shell Variables & Expansions

## 0-alias

This script creates an alias named `ls` that deletes all files in the current directory.

- The alias overrides the `ls` command with `rm *`.
- When the script is sourced (`source ./0-alias`), any call to `ls` will instead delete all non-hidden files.
- Using `\ls` bypasses the alias and runs the real `ls` command.

⚠️ **Use this script only in test directories.**

