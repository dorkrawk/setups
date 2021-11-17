# Set Up Your Computer To Do Some Crystal

Official setup instructions

## Assumptions

* You have [homebrew]((https://brew.sh/)) installed

## Install asdf (a version manager)

Install via Homebrew
```
brew install asdf
```

Install asdf-crystal plugin
```
asdf plugin-add crystal https://github.com/asdf-community/asdf-crystal.git

# set to use .crystal_version file
echo "legacy_version_file = yes" >>~/.asdfrc
```

## Now Install Crystal Using asdf

```
asdf install crystal 1.2.2 # or whatever the current version is

asdf list crystal

asdf global cyrstal 1.2.2
```

## Confirm

```
crystal -version
```
 


