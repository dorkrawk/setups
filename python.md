# Set Up Your Computer To Do Some Ruby

Why is running Python so messy?

## Assumptions

* You have [homebrew]((https://brew.sh/)) installed

## Install/Setup Via pyenv

```
brew install pyenv

pyenv install 3.8 # or whatever the current version is

pyenv global 3.8

# set your shell to load python from pyenv (change .zshrc to .bash_profile, if needed)
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.zshrc
```
