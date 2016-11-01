# Bash Echo Styling

A simple Bash include to add text styling to your `echo` output. 

This is generally most helpful for installation scripts and the like.

## Contents

The Bash Echo Styling package has three different includes that you can use depending on your needs.

### `colorsplus`

The `colorsplus` script is put together to cause the least amount of pain with variable conflicts. The syntax for the tags is terse, yet easy to follow.

### `colors`

The `colors` script is set up to be a _verbose_ option to the `colorsplus` file. The tag names are "literal" and a bit more verbose.

### `emojis`

The `emojis` script is a dropin for adding emojis content to the `echo` commands. After "sourcing" the file, you can add an emoji like so:

```bash
#!/bin/bash
echo -e "Get happy ${E_HAPPY}"
```