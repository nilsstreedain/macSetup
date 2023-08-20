# macSetup
Repo detailing my personal macOS setup process (In progress)

## Install Homebrew
Download/run Homebrew install script:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Add Homebrew to PATH
```
echo 'eval $(/opt/homebrew/bin/brew shellenv)' >> $HOME/.zprofile
```

Disable Homebrew analytics:
```
brew analytics off
```

## Install Apps From Brewfile
Download/run brewfile (Sign into App Store before running):
```
brew bundle --file=<(curl -fsSL https://raw.githubusercontent.com/nilsstreedain/brewfile/main/Brewfile) 
```

Enable HomeBrew Auto-update
```
brew autoupdate start --upgrade --greedy --cleanup
```
