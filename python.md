# Set Up Your Computer To Do Some Python

Why is running Python so messy?

## Assumptions

* You have [homebrew]((https://brew.sh/)) installed

## Install/Setup Via pyenv

```
brew install pyenv

pyenv install 3.10.0 # or whatever the current version is

pyenv global 3.10.0

# set your shell to load python from pyenv (change .zshrc to .bash_profile, if needed)
echo 'eval "$(pyenv init --path)"' >> ~/.zprofile

echo 'eval "$(pyenv init -)"' >> ~/.zshrc
```

## Confirm
```
which python
# should be [home dir]/.pyenv/shims/python
python --version
```
