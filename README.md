# Biscuit

A minimal fish shell prompt.

![Screenshot](https://i.imgur.com/n9YvfXy.png)

### Dependencies

- fish > 3.1.0
- A nerd font. `Iosevka NF` is recommended.

#### Install

```fish
fisher install projekt0n/biscuit
```

#### Configuration

#### Displaying the Current Git Branch

To display the current Git branch in the command prompt, set the `biscuit_show_branch_name` variable in the `config.fish` file located in the `$__fish_config_dir` directory.

```fish
set biscuit_show_branch_name 1
# ...
```

## Copying

This project is released under the terms of the GPLv3 license.
See [LICENCE](./LICENSE) for more information or see
[opensource.org](https://opensource.org/licenses/GPL-3.0)
