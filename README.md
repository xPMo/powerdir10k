# Powerdir10k

This is a fork which implements changes which I like in [my current zsh theme](https://github.com/xPMo/twodir-zsh-theme):

- [x] Adds support for named directory expansion (and arbitrary zsh directory prompt sequences)
- [ ] Adds support a customizable separator in between git up/down status
- [ ] Adds support for more permission information on the current directory

## Breaking changes in this fork:

I replace `POWERLEVEL9K_DIR_PATH_ABSOLUTE` with `POWERLEVEL9K_DIR_PROMPT_SEQUENCE`.
To use absolute paths in your prompt, you must use the variable like so:

```zsh
# you can also specify any prompt sequence
# as descrbed in `man zshmisc'
POWERLEVEL9K_DIR_PROMPT_SEQUENCE='%/'
```
